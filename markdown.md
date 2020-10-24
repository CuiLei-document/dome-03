# 学习内容

## img 图片标签
#### 作用
1. 发出get请求展示出一张图片
2. 属性有：src(路径) height(高) width(宽) alt(提示信息)
3. 事件： onload(加载成功) onerror(加载失败)
4. 响应式: max-width: 100%; 手机自适应屏幕大小宽度


## form 表单标签
#### 作用
1. 发出get或POST请求 发出页面请求
2. 属性： action(请求去哪个页面) method(发出get或者POST请求) autocomplete(用户建议) target(请求到哪个页面需要刷新)
3. 事件： onsubmit事件 form表单必须有sunmit才可以提交

#### input 有哪些属性
    <input type='text'> 文本框
    <input type='submit'> 提交
    <input type='checkbox'> 多选框
    <input type='radio'> 单选框
    <input type='file'> 上传单个文件
    <input type='file' multiple> 上传多个文件
    <input type='hidden'> 隐藏
    <input type='email'> 邮箱
    <input type='search'> 搜索
    <input type='color'> 颜色
    <input type='password'> 密码
    <input type='tel'> 手机
    <input type='number'> 数字
    <input type='date'> 时间
    <textarea></textarea> 留言框
    <select>
        <option></option>
    </select>

事件： onchange(用户改变触发的事件) onfocus(用户鼠标集中在input上触发的事件) onblur(用户鼠标出来的时候触发的事件)

验证器：
H5验证器

注意事件： 
1. 一般不监听input的click事件
2. form里面的input 要有name
3. form里面的要放一个 type=submit 才能触发submit事件

#### 其他标签

1. video 视频标签
2. audio 音频标签
3. canvas 画画标签
4. svq 矢量画画 
