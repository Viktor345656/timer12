class TestWin(QWidget):
    def timer_test(self):
        time QTime(0, 1, 0)
        self.timer = QTimer()
        self.timer.timeout.connect(self.timer3Event)
        self.timer.start(1000)
second_win.py
class TestWin(QWidget)
    def timer1Event(self):
        global time
        time = time.addSecs(-1)
