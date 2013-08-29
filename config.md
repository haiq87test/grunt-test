# grunt.config([prop [, value]])

## 概述

获取或设置配置。

## 参数

### prop:String

单个配置的键。

### value:String

单个配置的值。

## 例子

当没有传入参数时，获取全部配置数据。

    //grunt.config.init({ name: '{#domain#}',  project: '{#domain#}' });
    grunt.config(); //{ name : '{#domain#}',  project : '{#domain#}' }

当只传入一个参数时，获取一个配置的值，等同于调用 `grunt.config.get()` 。

    grunt.config('name'); //{#domain#}

当传入两个参数时，设置一个配置的值，等同于调用 `grunt.config.set()` 。

    grunt.config('name', '{#domain#}');