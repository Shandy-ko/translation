#�`���[�g���A��
## �V���v���ȃy�C���g�A�v���P�[�V����

���̃`���[�g���A���ł́A���Ȃ����A�ŏ��ɃE�B�W�F�b�g���쐬������@�������Ă��܂��B
Kivy�A�v���P�[�V�������v���O���~���O����ہA���Ȃ�������̖ړI���߂ɃJ�X�^���v�f��
�V�������[�U�[�C���^�[�t�F�[�X���쐬���邽�߂̍ł��d�v�Ȓm����񋟂��܂��B

## ��{�I�ȍl������
�A�v���P�[�V�������쐬����O�ɁA�������g�ŏd�v��3�̍��ڂ��m���߂�K�v������܂��B
�E���̃A�v���P�[�V�����E�v���Z�X�͂ǂ̂悤�ȃf�[�^�ł����H
�E�ǂ̂悤�ɁA���͎��o�I�ɂ��̃f�[�^��\���܂����H
�E�ǂ̂悤�Ƀ��[�U�[�����̃f�[�^�ƑΘb���܂����H

���Ƃ��΁A���Ȃ������ɒP���Ȑ���A�v���P�[�V�������L�q�������̂ł���΁A
���[�U�[�͎w�ŃX�N���[���ɕ`�悷�邱�Ƃ����Ԃ�]�݂܂��B



'''
from kivy.app import App
from kivy.uix.widget import Widget


class MyPaintWidget(Widget):
    pass


class MyPaintApp(App):
    def build(self):
        return MyPaintWidget()


if __name__ == '__main__':
    MyPaintApp().run()
'''

#�|��

'''
from kivy.app import App
from kivy.uix.widget import Widget


class MyPaintWidget(Widget):
    def on_touch_down(self, touch):
        print(touch)


class MyPaintApp(App):
    def build(self):
        return MyPaintWidget()


if __name__ == '__main__':
    MyPaintApp().run()
```

