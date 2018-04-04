# slide2
轮播2.0 --无缝轮播 <br>
缺点是没有按键和左滑右滑,<br>
思路： 状态机定理，分为三个状态：leave，current，enter.一开始第一张current，后面两张enter。接着current—>leave,enter->current,马上leave->enter，循环下去。
