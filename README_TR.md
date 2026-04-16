[![Gitpod'da Aç](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/EddieHubCommunity/good-first-issue-finder)\
[![RepoRater](https://repo-rater.eddiehub.org/api/badge?owner=EddieHubCommunity&name=good-first-issue-finder)](https://repo-rater.eddiehub.org/rate?owner=EddieHubCommunity&name=good-first-issue-finder)
![GitHub kod boyutu (bayt)](https://img.shields.io/github/languages/code-size/EddieHubCommunity/good-first-issue-finder?style=plastic)
![GitHub katkıda bulunanlar](https://img.shields.io/github/contributors/EddieHubCommunity/good-first-issue-finder)
[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=plastic&logo=discord&logoColor=white)](https://discord.com/invite/jZQs6Wu)

# EddieHub - İyi Bir İlk Konu (Good First Issue) Bulucu

İyi Bir İlk Konu Bulucu, yeni açık kaynak katkıda bulunanların "iyi ilk konular" (good first issues) aracılığıyla açık kaynak dünyasına giriş yapmalarını kolaylaştırmaya yardımcı olur.

![eddiehub konu bulucu](https://github.com/user-attachments/assets/093b84ac-0fb8-43ab-aa55-0992a01d8fc5)

## 👨‍💻 Canlı Versiyon

Web sitesine göz atın: [Good First Issue Finder](https://finder.eddiehub.org)

## 👇 Ön Koşullar

Kurulumdan önce lütfen aşağıdaki araçların sisteminizde yüklü olduğundan emin olun:

- [Git](https://git-scm.com/downloads)
- [NodeJs](https://nodejs.org/en/download/)

## 🛠️ Kurulum Adımları

1. Projeyi [buradan](https://github.com/EddieHubCommunity/good-first-issue-finder/fork) çatallayın (Fork)
2. Projeyi klonlayın
   ```bash
     git clone https://github.com/KULLANICI_ADINIZ/good-first-issue-finder.git
   ```
3. Proje dizinine gidin: `cd good-first-issue-finder`
4. Bağımlılıkları yükleyin: `npm install`
5. Eğer `engine not compatible with your version on node/npm` gibi bir hata alırsanız:

   Node sürümünüzü [Buradan](https://nodejs.org/en/) yükseltin.

   VEYA

   [Buradaki](https://www.geeksforgeeks.org/how-to-update-node-js-and-npm-to-next-version/) komutları takip edin.

   Node'un güncel LTS sürümünü yüklemenizi şiddetle öneririz.

6. Projenin kök dizininde bir `.env` dosyası oluşturun. Ardından GitHub Oauth değerlerinizi ekleyin (`.env.example` dosyasındaki örneğe bakın)

> **Not:** Gerekli değerleri almak için GitHub'da bir Oauth Uygulaması (GitHub Uygulaması değil) kurmanız gerekir. Belgeleri [burada](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app) bulabilirsiniz.
> Geri Çağırma URL'sinin (Callback Url) uygulamanın çalışacağı baseURL endpoint'ine işaret etmesi gerekir: `http://localhost:5173/api/authentication/callback`.
> Ayrıca, .env dosyasını asla commit etmeyin, Git tarafından yoksayılır.

<img width=450 alt="callback url" src="https://user-images.githubusercontent.com/75534912/191059977-48962f25-4a83-4564-9a17-019ab0783a40.jpg" />

7. `npm run dev` komutunu çalıştırın

Alternatif olarak, tüm adımları atlayarak [![Gitpod Göreve Hazır](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/good-first-issue-finder) kullanın.

> **Not:** Gitpod kullansanız bile 6. adımı yapmanız gerekmektedir.

## 🧪 Test Etme

Uçtan Uca (End-To-End) testleri çalıştırmak için [Playwright](https://playwright.dev/) kullanıyoruz.
Testleri çalıştırmak için şu komutu kullanarak playwright bağımlılıklarını yüklemeniz gerekir:

```bash
npx playwright install --with-deps
```

## 👨‍💻 Katkıda Bulunma

- Katkılar, açık kaynak topluluğunu öğrenmek, ilham almak ve yaratmak için harika bir yer haline getirir.
- Yapacağınız her türlü katkı **büyük takdir toplar**.
- Daha fazla bilgi için [katkıda bulunma kılavuzumuza](/CONTRIBUTING.md) göz atın.

## 🛡️ Lisans

Good First Issue Finder, MIT Lisansı ile lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 💪 Tüm Katkıda Bulunanlara Teşekkürler

Good First Issue Finder'ın büyümesine yardımcı olduğunuz için çok teşekkürler. Harikasınız! 🍻

[![Katkıda Bulunanlar](https://contrib.rocks/image?repo=EddieHubCommunity/good-first-issue-finder)](https://github.com/EddieHubCommunity/good-first-issue-finder/graphs/contributors)

## 🙏 Destek

Bu projenin sizden bir ⭐️'a ihtiyacı var. Yıldız bırakmayı unutmayın ⭐️.

## Sözümüz

Topluluğumuza katılımın herkes için tacizsiz bir deneyim olmasını amaçlıyoruz ve açık, samimi, çeşitli ve kapsayıcı bir topluluğa katkıda bulunacak şekilde hareket etmeyi taahhüt ediyoruz.

Kabul edilemez bir davranışla karşılaştıysanız veya size bildirildiyse, lütfen bunu rapor edebileceğinizi unutmayın. [Davranış Kurallarımızı](https://github.com/EddieHubCommunity/good-first-issue-finder/blob/main/CODE_OF_CONDUCT.md) okuyun.
