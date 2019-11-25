import pygame
import pygame as pg
import socket
import struct

sock = socket.socket()
# sock.bind(('192.168.0.1', 9090))  # первое - хост 192.168.0.1, второе порт
# sock.listen(1)
# conn, addr = sock.accept()
# print(1111111111)


class Сommunication:
    def __init__(self):
        pg.font.init()
        pygame.init()
        pygame.display.init()
        pygame.joystick.init()
        pygame.joystick.Joystick(0).init()
        # pygame инициализация модулей
        self.x = 0  # 0
        self.y = 0  # 1
        self.w = 0  # 2
        self.z = 0  # 3
        self.t = 0  # 4

        self.but_1_g2 = False
        self.but_2_g2 = False
        self.but_3_g2 = False
        self.but_4_g2 = False
        self.but_5_g2 = False
        self.but_6_g2 = False

        self.but_1_g1 = False
        self.but_2_g1 = False
        self.but_3_g1 = False
        self.but_4_g1 = False
        self.but_10 = False
        self.but_11 = False
        self.os_data = [self.x, self.y, self.w, self.z, self.t]
        self.rotarycamera = (0, 0)
        self.bool_buttons = [self.but_1_g2, self.but_2_g2, self.but_3_g2,
                             self.but_4_g2, self.but_5_g2, self.but_6_g2,
                             self.but_1_g1, self.but_2_g1, self.but_3_g1,
                             self.but_4_g1, self.but_10, self.but_11]

        self.w_data = [self.x, self.y, self.w, self.z, self.t,
                       self.bool_buttons, self.rotarycamera]

    def Jostik_info(self):
        #  self.JoyName = pygame.joystick.Joystick(0).get_name()
        # JoyAx = pygame.joystick.Joystick(0).get_numaxes()
        # Joybutton = pygame.joystick.Joystick(0).get_numbuttons()
        # Joynumhats = pygame.joystick.Joystick(0).get_numhats()
        self.w = pygame.joystick.Joystick(0).get_axis(2)
        if self.w == -3.0517578125e-05:
            self.w = 0.0
        self.w = int(self.w * 100)
        if self.w == 99:
            self.w = 100

        self.t = pygame.joystick.Joystick(0).get_axis(4)
        if self.t == -3.0517578125e-05:
            self.t = 0.0
        self.t = int(self.t * 100)
        if self.t == 99:
            self.t = 100

        self.x = pygame.joystick.Joystick(0).get_axis(0)
        if self.x == -3.0517578125e-05:
            self.x = 0.0
        self.x = int(self.x * 100)
        if self.x == 99:
            self.x = 100

        self.y = pygame.joystick.Joystick(0).get_axis(1)
        if self.y == -3.0517578125e-05:
            self.y = 0.0
        self.y = int(self.y * 100)
        if self.y == 99:
            self.y = 100

        self.z = pygame.joystick.Joystick(0).get_axis(3)
        if self.z == -3.0517578125e-05:
            self.z = 0.0
        self.z = int(self.z * 100)
        if self.z == 99:
            self.z = 100

        self.but_1_g2 = bool(pygame.joystick.Joystick(0).get_button(4))
        self.but_2_g2 = bool(pygame.joystick.Joystick(0).get_button(5))
        self.but_3_g2 = bool(pygame.joystick.Joystick(0).get_button(6))
        self.but_4_g2 = bool(pygame.joystick.Joystick(0).get_button(7))
        self.but_5_g2 = bool(pygame.joystick.Joystick(0).get_button(8))
        self.but_6_g2 = bool(pygame.joystick.Joystick(0).get_button(9))
        # !!
        self.but_1_g1 = bool(pygame.joystick.Joystick(0).get_button(0))
        self.but_2_g1 = bool(pygame.joystick.Joystick(0).get_button(1))
        self.but_3_g1 = bool(pygame.joystick.Joystick(0).get_button(2))
        self.but_4_g1 = bool(pygame.joystick.Joystick(0).get_button(3))
        self.rotarycamera = pygame.joystick.Joystick(0).get_hat(0)
        # !!
        self.but_10 = bool(pygame.joystick.Joystick(0).get_button(10))
        self.but_11 = bool(pygame.joystick.Joystick(0).get_button(11))

    def display(self):
        self.win = pg.display.set_mode((800, 600))
        pg.display.set_caption('Джостик')
        f1 = pygame.font.Font(None, 24)
        pygame.event.pump()
        self.win.fill((255, 255, 255))

        os2_1_g2_text = f1.render(f'ось w: {self.w}', 1, (180, 0, 0))
        os4_2_g2_text = f1.render(f'ось t: {self.t}', 1, (180, 0, 0))
        but_1_g2_text = f1.render(f'Скорость 1 кнопка: {self.but_1_g2}', 1, (180, 0, 0))
        but_2_g2_text = f1.render(f'Скорость 2 кнопка: {self.but_2_g2}', 1, (180, 0, 0))
        but_3_g2_text = f1.render(f'Скорость 3 кнопка: {self.but_3_g2}', 1, (180, 0, 0))
        but_4_g2_text = f1.render(f'Скорость 4 кнопка: {self.but_4_g2}', 1, (180, 0, 0))
        but_5_g2_text = f1.render(f'Скорость 5 кнопка: {self.but_5_g2}', 1, (180, 0, 0))
        but_6_g2_text = f1.render(f'Скорость 6 кнопка: {self.but_6_g2}', 1, (180, 0, 0))

        os0_g1_text = f1.render(f'x ось: {self.x}', 1, (180, 0, 0))
        os1_g1_text = f1.render(f'y ось: {self.y}', 1, (180, 0, 0))
        os3_g1_text = f1.render(f'z ось: {self.z}', 1, (180, 0, 0))
        but_1_g1_text = f1.render(f'Управление 1 кнопка: {self.but_1_g1}', 1, (180, 0, 0))
        but_2_g1_text = f1.render(f'Управление 2 кнопка: {self.but_2_g1}', 1, (180, 0, 0))
        but_3_g1_text = f1.render(f'Управление 3 кнопка: {self.but_3_g1}', 1, (180, 0, 0))
        but_4_g1_text = f1.render(f'Управление 4 кнопка: {self.but_4_g1}', 1, (180, 0, 0))
        rotarycamera = f1.render(f'rotarycamera: {self.rotarycamera}', 1, (180, 0, 0))

        but_10_text = f1.render(f'Доп. кнопка 1: {self.but_10}', 1, (180, 0, 0))
        but_11_text = f1.render(f'Доп. кнопка 2: {self.but_11}', 1, (180, 0, 0))

        self.win.blit(os2_1_g2_text, (10, 50))
        self.win.blit(os4_2_g2_text, (10, 75))
        self.win.blit(but_1_g2_text, (10, 100))
        self.win.blit(but_2_g2_text, (10, 125))
        self.win.blit(but_3_g2_text, (10, 150))
        self.win.blit(but_4_g2_text, (10, 175))
        self.win.blit(but_5_g2_text, (10, 200))
        self.win.blit(but_6_g2_text, (10, 225))
        # !!
        self.win.blit(os0_g1_text, (300, 50))
        self.win.blit(os1_g1_text, (300, 75))
        self.win.blit(os3_g1_text, (300, 100))
        self.win.blit(but_1_g1_text, (300, 125))
        self.win.blit(but_2_g1_text, (300, 150))
        self.win.blit(but_3_g1_text, (300, 175))
        self.win.blit(but_4_g1_text, (300, 200))
        self.win.blit(rotarycamera, (300, 225))
        # !!
        self.win.blit(but_10_text, (300, 400))
        self.win.blit(but_11_text, (300, 425))
        pg.display.update()

    def read(self, data):
        pass

    def return_os(self):
        return self.os_data, self.bool_buttons, self.rotarycamera

    def return_buttons(self):
        return self.bool_buttons

    def return_rotarycamera(self):
        return self.rotarycamera


class InputPacket:
    def __init__(self):
        # данные храняться в байтовом виде в кучке
        self.W1_data = bytearray()

    def return_(self):
        return self.W1_data
    
    def input_(self, os_data, bool_buttons, rotarycamera):
        self.W1_data = bytearray()
        for i in os_data:
            self.W1_data += struct.pack("b", i)

        for i in bool_buttons:
            self.W1_data += struct.pack("b", i)

        for i in rotarycamera:
            self.W1_data += struct.pack("b", i)


class OutputPacket:
    def __init__(self):
        self.W2_data = []

    def return_(self):
        return self.W2_data

    def input_(self, data_r):
        self.W2_data = []
        for i in data_r:
            self.W2_data.append(i)


com = Сommunication()
InPac = InputPacket()
Outpuc = OutputPacket()
while True:
    com.Jostik_info()
    InPac.input_(com.return_os(), com.return_buttons(), com.return_rotarycamera())
    com.display()
    # data = conn.recv(1024)
    # Outpuc.input_(data)
    # if data:
    #     com.read(data)
    #     conn.send(com.write())
# conn.close()
