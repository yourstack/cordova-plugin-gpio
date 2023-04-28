# Cordova Plugin Gpio
- name: cordova-plugin-gpio

# TODOLIST
- [ ] Support Capacitorjs.com
- [ ] Typescript Declaration

# Depands
- APIDoc: https://developer.android.google.cn/reference/com/google/android/things/pio/package-summary
- Version: https://mvnrepository.com/artifact/com.google.android.things/androidthings
- Cordova Plugin: https://cordova.apache.org/docs/en/latest/plugin_ref/spec.html#framework

# Conflict
- 当应用希望打包成普通Android应用，但在主板运行时包含此插件
    - package.json中删除本插件
    - 在独立打包主板程序时，添加
    ``` sh
    "cordova-plugin-gpio": "github:yourstack/cordova-plugin-gpio",
    ```

# Contributor
- [ryanemax](https://github.com/ryanemax)