PuBuImageLoader
===============

#ͼƬ�������
#�汾��1.2.0
������
1.������Բ�ǹ���
2.������ͼƬ��������
3.�ṩ��ͼƬ������ؿ���





ʹ��˵����
imageLoader = PubuAsynImageLoader.getInstanceof(context);   //�õ�������ʵ��
 
imageLoader.setDefaultResource(R.drawable.icon_null);      //����Ĭ�ϼ���ͼƬ


imageLoader.setImgLoadSwitch(loading);   //�����������ͼƬ����

//2�ַ�ʽ����ͼƬ���붯����������Ĭ���ǽ��䶯��
imageLoader.setAnimOfImage(Animation animation);
imageLoader.setAnimOfImage(int AnimResource);

//2�ּ���ͼƬ��ʽ
imageLoader.loadBitMap(iv, imageUrl, callBack, needRoundCorner, RoundCornerPixels);   //�ֹ���ʽ��ʹ�ûص��Լ�����
imageLoader.loadBitMap(iv, imageUrl, type, needRoundCorner, RoundCornerPixels);       //�Զ���ʽ��ʹ��typeȷ��ͼƬ������(src or background)



imageLoader.clearAllCache(callBack)  //���ͼƬ����
