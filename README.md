# D-AUDIO!
### A Custom Audio for Your HTML Page!
Yup, seperti deskripsi singkatnya. Ini custom tag audio untuk HTML kita!
## INSTALASI (INSTALLATION)
Letakan tag script ini pada bagian sebelum penutup body
```html
<script src="https://cdn.statically.io/gh/devanka761/custom-audio-html/main/dAudio.js"></script>
```
## PENGGUNAAN (HOW TO USE)
Cukup gunakan tag di bawah ini selayaknya tag ```<audio>```.
```html
<d-audio src="PATHAUDIO.mp3"><d-audio>
```
## KUSTOMISASI THUMB (CUSTOM THUMB)
Ada 3 tipe thumb yang bisa dipakai. Yaitu lingkaran (circle), persegi (square), dan persegi panjang (rectangle).
> ### Linkaran (default)
> ```html
> <d-audio src="PATHAUDIO.mp3"><d-audio>
> ```
> ### Persegi
> ```html
> <d-audio class="square" src="PATHAUDIO.mp3"><d-audio>
> ```
> ```html
> <d-audio class="rectangle" src="PATHAUDIO.mp3"><d-audio>
> ```
## KOSTUMISASI TEMPLATE WARNA (CUSTOM COLOURS)
> Setelah Meletakkan Script Instalasi, jalankan
> ```javascript
> dAudio.custom();
> ```
> Kemudian, letakan kode css di bawah ini ke dalam tag ```<style>``` atau letakan di file css yang sudah dihubungkan
> ```css
> :root {
>     --dAudioBg: #555555;
>     --dAudioPlay: #ffa500;
>     --dAudioPause: #ffa500;
>     --dAudioStop: #ffa500;
>     --dAudioThumb: #ffa500;
>     --dAudioTrack: #2b2b2b;
>     --dAudioText: #ffffff;
> }
[SUBSCRIBE DEVANKA761 :V](https://www.youtube.com/c/RG761)