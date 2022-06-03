# Zehirli-balik-tespiti-poisonous-fish-detection-
Daha detaylı bigi ve video için:detayli bilgi için:https://github.com/nicknochnack/TFODCourse
Dataset bing search API ile olusturuldu 1 ay ucretsiz deneme surumu için:https://www.microsoft.com/en-us/bing/apis/bing-web-search-api
bing search api kullanmak için linkten kayıt olup api keyinizi azure.py kısmındaki yere yapıstırınız.
 Konsola asagıdaki komutları yazın
 mkdir dataset/trakonya
python azure.py --query "trakonya" --output dataset/trakonya
Dataset olusturdukdan sonra calısma ortamı olusturup aktive ediniz.
python -m venv zehirli
.\zehirli\Scripts\activate
Jupyter notebook kurulumu için:
python -m pip install --upgrade pip
pip install ipykernel jupyter
python -m ipykernel install --user --name=zehirli
konsola jupyter notebook yazıp giriş yapın.

Bazı sonuclar:
![trakonya](https://user-images.githubusercontent.com/102317496/171771921-42e1045a-dc8a-4c42-947f-27ac741ecc07.png)
![Adsız](https://user-images.githubusercontent.com/102317496/171771928-5ec8d8e8-46ca-4621-92c5-866a4954518a.png)
![isko](https://user-images.githubusercontent.com/102317496/171771946-ca5f7f3c-1ad3-4783-bb23-8d9366a273f7.png)



