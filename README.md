# Naive-Bayes-Algorithm       
Naive Bayes algoritması makine öğrenmesi yöntemlerinde kullanılan yöntemlerden biridir. Makine Öğrenmesinde verilerin sınıflandırılması için kullanılır.
Bayes teoremini kullanarak, B oluşumu göz önüne alındığında, A olma olasılığını bulabiliriz. Burada B, kanıt ve A ise hipotezdir. Burada yapılan varsayım, yordayıcıların / özelliklerin bağımsız olduğu şeklindedir. Bu, belirli bir özelliğin varlığı diğerini etkilemez. Bu yüzden Naive denir.    
</br>



ÇALIŞMA MANTIĞI                      
Öncelikle verilerimizi frekans tablosuna çeviriyoruz ve olasılıkları hesaplıyoruz. Olasılık hesapladığımız için olasılıkların 0 çıkması bizim için mantıksal sorunlar çıkartabilir o yüzden bunun önüne geçmek için bütün frekans tablosundaki her değere bir ekliyoruz. Sonrasında Bayes teoremini uygulamaya başlıyoruz.            
![Thomas_Bayes](https://user-images.githubusercontent.com/72493647/207050561-06ace2ae-2848-4e77-93fe-81c90b2eb9d2.png)                   
P(A|B) ; B olayı gerçekleştiği durumda A olayının meydana gelme olasılığıdır (bakınız koşullu olasılık )                  
P(B|A) ; A olayı gerçekleştiği durumda B olayının meydana gelme olasılığıdır                     
P(A) ve P(B) ; A ve B olaylarının önsel olasılıklarıdır.                    
</br>
</br>




EĞİTİM ve TEST                      
Veriler test verisi ve eğitim verisi olarak ayrılmalıdır.              
![Siniflandirma_Notlari_14_Python_Naive_Bayes_Egitim_Seti_Grafik](https://user-images.githubusercontent.com/72493647/207053187-d1cd2cf5-7d2f-44f3-9719-371dafd09c6b.png)
![Siniflandirma_Notlari_14_Python_Naive_Bayes_Test_Seti_Grafik](https://user-images.githubusercontent.com/72493647/207053194-144dd06f-321a-4569-8269-6e67d9bb8da2.png)

</br></br>
KULLANIM ALANLARI                         
Naive Bayes, bir çok farklı alanda kullanılabilir.              
Örneğin, bir email sınıflandırma sistemi, gelen email'leri spam veya non-spam olarak sınıflandırabilir. Bir banka müşteri verisi üzerinde Naive Bayes algoritması kullanarak, müşterilerin kredi notlarını tahmin edilebilir ve kredi verme kararlarını buna göre belirlenebilir. Veya hastalık tanısında kullanılabilir.

![13054_2020_2962_Fig1_HTML](https://user-images.githubusercontent.com/72493647/207059019-904d4d52-0d84-40de-b9c2-93069d7d4a43.png)
