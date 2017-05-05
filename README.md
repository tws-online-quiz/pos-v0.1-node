# POS Project v0.1

POS收银机 版本：v0.1

## 教学目标

1. 学会把基本描述转换成程序；
2. 熟悉循环嵌套的使用；

## 需求描述

商店里进行购物结算时会使用收银机（POS）系统，这台收银机会在结算时根据客户的购物车（Cart）中的商品（Item）进行结算和打印购物清单。

我们需要实现一个函数，该函数能够将指定格式的数据作为参数输入，然后在返回值中输出结算清单的文本。

输入格式（样例）：

```javascript

[
    {
        barcode: 'ITEM000000',
        name: '可口可乐',
        unit: '瓶',
        price: 3.00

    },
    {
        barcode: 'ITEM000000',
        name: '可口可乐',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000000',
        name: '可口可乐',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000000',
        name: '可口可乐',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000000',
        name: '可口可乐',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000001',
        name: '雪碧',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000001',
        name: '雪碧',
        unit: '瓶',
        price: 3.00
    },
    {
        barcode: 'ITEM000004',
        name: '电池',
        unit: '个',
        price: 2.00
    }
]

```

清单内容（样例）：

```
***<没钱赚商店>购物清单***
名称：可口可乐，数量：5瓶，单价：3.00(元)，小计：15.00(元)
名称：雪碧，数量：2瓶，单价：3.00(元)，小计：6.00(元)
名称：电池，数量：1个，单价：2.00(元)，小计：2.00(元)
----------------------
总计：23.00(元)
**********************
```

## 作业要求

1. 根据```spec/main-spec.js```中的测试用例，在```src/main.js```文件中编写实现代码并确保测试通过；
2. 请在保证代码可读性的前提下，尽可能用最少的代码行数完成作业；
3. 将清单输出到控制台,使测试通过

## 作业提示


1. 学习将重复的内容合并再转化成清单