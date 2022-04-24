from PyQt5.QtWidgets import *
from PyQt5.QtGui import *
from PyQt5.QtCore import *
import sys

ONE = False
TWO = False
THREE = False

x = str([[1, 2, 5, 8, 9], [1, 2, 6, 7, 9], [1, 3, 4, 8, 9], [1, 3, 5, 7, 9], [1, 3, 6, 7, 8], [1, 4, 5, 6, 9],
         [1, 4, 5, 7, 8], [2, 3, 4, 7, 9], [2, 3, 5, 6, 9], [2, 3, 5, 7, 8], [2, 4, 5, 6, 8], [3, 4, 5, 6, 7]])


class Example(QMainWindow):

    def __init__(self):
        super().__init__()

        self.setGeometry(300, 300, 500, 300)
        self.setWindowTitle('GUI_Test_002')
        self.setWindowIcon(QIcon('img/web.png'))

        self.init_ui()

        self.show()

    def init_ui(self):
        QToolTip.setFont(QFont('SansSerif', 10))

        qb = QPushButton('Quit', self)
        qb.clicked.connect(QApplication.instance().quit)
        qb.resize(60, 25)
        qb.move(425, 260)

        self.top_input = QLineEdit(self)
        self.top_input.move(125, 25)
        self.top_input.resize(280, 25)

        self.bottom_input = QLineEdit(self)
        self.bottom_input.move(125, 55)
        self.bottom_input.resize(280, 75)
        self.bottom_input.setText(x)

        one_b = QPushButton('1', self)
        one_b.clicked.connect(self.one_clicked)
        one_b.resize(25, 25)
        one_b.move(25, 25)

        two_b = QPushButton('2', self)
        two_b.clicked.connect(self.two_clicked)
        two_b.resize(25, 25)
        two_b.move(55, 25)

        three_b = QPushButton('3', self)
        three_b.clicked.connect(self.three_clicked)
        three_b.resize(25, 25)
        three_b.move(85, 25)

        four_b = QPushButton('4', self)
        four_b.clicked.connect(self.four_clicked)
        four_b.resize(25, 25)
        four_b.move(25, 55)

        five_b = QPushButton('5', self)
        five_b.clicked.connect(self.five_clicked)
        five_b.resize(25, 25)
        five_b.move(55, 55)

        six_b = QPushButton('6', self)
        six_b.clicked.connect(self.six_clicked)
        six_b.resize(25, 25)
        six_b.move(85, 55)

        seven_b = QPushButton('7', self)
        seven_b.clicked.connect(self.seven_clicked)
        seven_b.resize(25, 25)
        seven_b.move(25, 85)

        eight_b = QPushButton('8', self)
        eight_b.clicked.connect(self.eight_clicked)
        eight_b.resize(25, 25)
        eight_b.move(55, 85)

        nine_b = QPushButton('9', self)
        nine_b.clicked.connect(self.nine_clicked)
        nine_b.resize(25, 25)
        nine_b.move(85, 85)

    def one_clicked(self):
        print("pressed 1")
        self.top_input.setText("1")
        self.show()

    def two_clicked(self):
        print("pressed 2")
        self.top_input.setText("2")
        self.show()

    def three_clicked(self):
        print("pressed 3")

    def four_clicked(self):
        print("pressed 4")

    def five_clicked(self):
        print("pressed 5")

    def six_clicked(self):
        print("pressed 6")

    def seven_clicked(self):
        print("pressed 7")

    def eight_clicked(self):
        print("pressed 8")

    def nine_clicked(self):
        print("pressed 9")


def main():

    app = QApplication(sys.argv)
    ex = Example()
    sys.exit(app.exec_())


if __name__ == '__main__':
    main()
