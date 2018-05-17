# Something About Regular Expression
## 什么是正则表达式
  正则表达式(*Regular Expression*)是指使用单个字符串来描述、匹配一系列符合某个句法规则的字符串.
## RegExp对象
  JavaScript通过内置对象RegExp支持正则表达式，有两种方法实例化RegExp对象：
  
  1.字面量
  
    `var reg = /\bis\b/g;`
    
  2.构造函数

    `var reg=new RegExp( '\\bis\\b' , 'g' );`
    
    *修饰符*
    
    · g:global全文搜索，不添加，搜索到第一个匹配停止
    
    · i:ignore case忽略大小写，默认大小写敏感
    
    · m:multiple lines多行搜索

## 注意事项
 1.特殊符号
 
 ！ $ ^ * + = | . ? \ / ( ) [ ] { }
 
 2.特殊字符
 
 o t n v f r xnn uxxxx cX
