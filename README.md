PROGRAMOWANIE FULL-STACK W CHMURACH OBLICZENIOWYCH - Zadanie 1

CZĘŚĆ OBOWIĄZKOWA
1. (max. 10%)
Proszę napisać program serwera (dowolny język programowania), który realizować będzie
następującą funkcjonalność:

a. po uruchomieniu kontenera, serwer pozostawia w logach informację o dacie
uruchomienia, imieniu i nazwisku autora serwera (imię i nazwisko studenta) oraz porcie
TCP, na którym serwer nasłuchuje na zgłoszenia klienta.

![286278029_1388569494973506_7101434773537742449_n](https://user-images.githubusercontent.com/78439685/173583030-5e66c348-c5f3-498f-94ee-eaee025e5b29.png)

Aby zobaczyć logi należy użyć polecenia ze screena:
![286989491_416096753724754_8403101039764072754_n](https://user-images.githubusercontent.com/78439685/173583421-fd801918-46e7-4b06-9e68-9127828936ad.png)

b. na podstawie adresu IP klienta łączącego się z serwerem, w przeglądarce powinna zostać
wyświetlona strona informująca o adresie IP klienta i na podstawie tego adresu IP, o dacie
i godzinie w jego strefie czasowej. 

Działanie aplikacji:

![0](https://user-images.githubusercontent.com/78439685/173586998-858165c5-1db8-4da0-8f7d-c34b7c490ab1.png)


Kod aplikacji: 

![287567379_2316022408539179_5247091505453976677_n](https://user-images.githubusercontent.com/78439685/173584034-a7af19aa-694a-44e9-89a2-3457abbdc336.png)

2. (max. 50%)
Opracować plik Dockerfile, który pozwoli na zbudowanie obrazu kontenera realizującego
funkcjonalność opisaną w punkcie 1. Przy ocenie brane będzie sposób opracowania tego pliku
(dobór obrazu bazowego, wieloetapowe budowanie obrazu, ewentualne wykorzystanie warstwy
scratch, optymalizacja pod kątem funkcjonowania cache-a w procesie budowania). Dockerfile
powinien również zawierać informację o autorze tego pliku (ponownie imię i nazwisko studenta). 
![287482382_760462281805661_2414292345176340407_n](https://user-images.githubusercontent.com/78439685/173584298-ba6606ae-01f0-4e69-a399-bb88f3834fbf.png)

3. (max. 20%)
Należy podać polecenia niezbędne do:

a. zbudowania opracowanego obrazu kontenera,
![286278029_1388569494973506_7101434773537742449_n](https://user-images.githubusercontent.com/78439685/173584578-2dd68d4f-8c1f-453c-97d6-865a79115297.png)

b. uruchomienia kontenera na podstawie zbudowanego obrazu,

oraz

c. sposobu uzyskania informacji, które wygenerował serwer w trakcie uruchamiana kontenera 
![285909604_437467184436267_5677568747304053384_n](https://user-images.githubusercontent.com/78439685/173584690-7cddb546-a0d4-4e6c-a2e2-896cc125d1c4.png)

d. sprawdzenia, ile warstw posiada zbudowany obraz.
![286516820_1241505156620769_3702256904017000889_n](https://user-images.githubusercontent.com/78439685/173584888-6be9b510-15d9-4fd3-8b61-affb53332318.png)

4. (max. 20%)
Zbudować obrazy kontenera z aplikacją opracowaną w punkcie nr 1, które będą pracował na
architekturach: linux/arm/v7, linux/arm64/v8 oraz linux/amd64. Obrazy te należy przesłać do
swojego repozytorium na DockerHub. W sprawozdaniu należy podać wykorzystane instrukcje wraz
z wynikiem ich działania I ewentualnymi komentarzami.
![286870054_447520443986333_7993713278223059287_n](https://user-images.githubusercontent.com/78439685/173585306-c39e0bc6-e78d-4766-a0aa-6573fa2d73c9.png)

![8](https://user-images.githubusercontent.com/78439685/173585474-56877d6b-bbbc-406b-b7e3-42c33e43ce26.png)

CZĘŚĆ DODATKOWA
-------------------------------------------------------------------------------------------
Wykonać punkt 4:
- z wykorzystaniem GitHubActions – max 40%

![11](https://user-images.githubusercontent.com/78439685/173596974-84982d49-3073-4006-84af-2fc7bb4cb882.png)

![image](https://user-images.githubusercontent.com/78439685/173597096-517c350f-5019-4250-a272-e6a8db7855d4.png)

- z przesłaniem danych nie na DockerHub a na repozytorium GitHub wraz z krótkim opisem
konfiguracji GitHub Container Registry – max. 20%
![12](https://user-images.githubusercontent.com/78439685/173597217-faf56e04-2ffa-4e24-8281-60d844b1f7ca.png)
![image](https://user-images.githubusercontent.com/78439685/173597309-d50571a4-f92a-4965-a65e-54a93333d9ef.png)

