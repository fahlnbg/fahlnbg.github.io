
if [ -e "Rls" ]
then echo ok
 else printf "Origin: GitPush Repo\nLabel: GitPush\nSuite: stable\nVersion: 1.0\nCodename: ios\nArchitecture: iphoneos-arm\nComponents: main\nDescription: Source Cydia Repo by GitPush <fahlnbg>\n" > Rls;
echo Bạn có thể sửa Release tại $FAH/$NameF/Rls;
fi