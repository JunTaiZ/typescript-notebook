## 基本类型
* 布尔值 Boolean
* 数字 Number
* 字符串 String
* 数组 Array
* 元组 Tuple
* 枚举 enum(关键字)
* Any
* Void
* Null, Undefined
* Never

### 0. 申明变量或常量的关键字
* **var**  
ES6前申明变量的关键字，会"变量提升"
* **let**  
ES6开始申明变量的关键字，块级作用域
* **const**  
ES6开始申明常量的关键字，块级作用域  

### 1. 布尔值 Boolean
### 2. 数字 Number
### 3. 字符串 String
### 4. 数组 Array
### 5. 元组 Tuple
### 6. 枚举 enum(关键字)
### 7. Any
### 8. Void
### 9. Null, Undefined
### 10. Never
### 11. 类型断言
类型断言相当强制转化类型
* 标识符 as 类型
```typescript
let someValue: any = "this is a string";

let strLength: number = (<string>someValue).length;
```
* <类型>标识符