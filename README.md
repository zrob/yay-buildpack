# yay-buildpack

Add some YAY to your app.

```
cf push MYAPP -b https://github.com/zrob/yay-buildpack -b USEFUL_BUILDPACK
cf logs MYAPP
cf run-task MYAPP yay
```
