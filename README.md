# mobileAuto

<!-- 当前设计尺寸750 根元素为100px  便于计算 -->
# document.documentElement.style.fontSize = ( innerWidth*100/750 ) + 'px';

<!-- 案例：如果你的设计稿是720 -->
# document.documentElement.style.fontSize = ( innerWidth*100/720 ) + 'px';

<!-- 如何使用 -->
# 设计稿如果是750px,在这个尺寸下我将根元素字体大小设置成100px,这样我设计稿上的元素高是98px的时候,我直接设置成0.98rem;这样简单的计算一下。