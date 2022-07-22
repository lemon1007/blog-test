# 自我介绍
## 我叫青砚，我的爱好有
* 阅读
* 游戏
* 电影
* 音乐
* 旅游
# 
## 我的经历
1.  计算机专业学生
2.  政府公务员
3.  未来的前端工程师（努力ing） 
#  
## 代码放段刚才做出来的题吧。
### 给出一个整数 x ，如果 x 是一个回文整数，返回 true ；否则，返回 false 。回文数是指正序（从左向右）和倒序（从右向左）读都是一样的整数。例如，121 是回文，而 123 不是。
```javascript
/**
 * @param {number} x
 * @return {boolean}
 */
var isPalindrome = function(x) {
 if (x < 0) return false
      var str = '' + x
      strChange = str.split('').reverse().join('')
      return strChange === str
    }
```
