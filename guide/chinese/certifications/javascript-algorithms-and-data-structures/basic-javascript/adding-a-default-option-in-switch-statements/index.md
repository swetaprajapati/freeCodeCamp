---
title: Adding a Default Option in Switch Statements
localeTitle: 在交换机语句中添加默认选项
---
# 在交换机语句中添加默认选项

*   添加默认选项可确保在您的变量与任何选项都不匹配的情况下，将使用默认选项。

## 解：

```javascript
function switchOfStuff(val) { 
  var answer = ""; 
 
  switch(val){ 
    case 'a': answer = 'apple'; 
    break; 
    case 'b': answer = 'bird'; 
    break; 
    case 'c': answer = 'cat'; 
    break; 
    default: answer = 'stuff'; 
  } 
 
  return answer; 
 } 

```