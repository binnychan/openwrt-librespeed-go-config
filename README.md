1. install "librespeed-go" package
2. edit "/etc/config/librespeed-go" and change the setting as "option enabled '0'" to "option enabled '1'"
3. restart the librespeed-go service (service librespeed-go stop; service librespeed-go status; service librespeed-go start ; service librespeed-go status)
4. browser to visit "http://[yourRouter]:8989"
5. Enjoy
 
Ref : https://openwrt.org/packages/pkgdata/librespeed-go
