原本通过<script>标签引入的脚本执行是会阻塞页面剩余部分的加载的

defer、async共同点：都是告诉浏览器不用等待脚本执行完毕再加载其他脚本

defer：延迟执行脚本，直到解析完</html>后，按推迟的顺序依从执行脚本

async：异步执行脚本，不能保证脚本的执行顺序，但能保证在页面的load事件前执行。



p.s 除了在html中用script标签，还可以用DOM API，document.appendChild('script')，动态加载脚本，默认是async的，可以通过script.async = false 关闭 