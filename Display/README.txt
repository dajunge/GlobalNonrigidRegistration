openGLWindow_ = new OpenGLWindow();
openGLWindow_->resize(w, h);
openGLWindow_->setWindowTitle("OpenGLWindow");
openGLWindow_->setFocusPolicy(Qt::TabFocus);//Qt::ClickFocus
openGLWindow_->show(); //һ��Ҫshowһ�����ڳ�ʼ��

openGLWindow_->SetVertexBuffer() //����ģ������,�����������������
����:
F1:��ɫ F2:phong����ģ��
1:�� 2:�� 3:��
r:��ԭ
����Ҽ�˫��ʰȡ��,�����ת,�н�ƽ��

����Qt��OpenCV