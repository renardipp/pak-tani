#Branch ini oki gunakan untuk mengupload versi-oki sebelum nantinya di-integrasikan dengan hasil kerja teman-teman.

## Deskripsi

Ini hanya template sederhana untuk otentikasi email dan password.
Dibuat dengan Ionic Framework dan Firebase JavaScript SDK.

Apa yang ada?

* Penyedia otentikasi beserta segala fungsinya.
* Login Page.
* Signup Page.
* Password Reset Page.

## Installasi

Clone repository dengan ssh:

```sh
$ git clone git@github.com:renardipp/pak-tani.git
$ cd pak-tani-oki
$ npm install
```

Clone repository dengan https:

```sh
$ git clone https://github.com/renardipp/pak-tani.git
$ cd pak-tani-oki
$ npm install
```

Setelah di clone, buka `app/credentials.ts`.

Firebase keys yang ada itu punya oki.

Ganti Firebase keysnya(kalau mau dipakai sebagai project sendiri) dengan keys punya sendiri.

Firebase keys bisa didapat di:
[the Firebase Console](https://console.firebase.google.com)

`app/credentials.backup.ts` itu struktur dasarnya//backup kalo ada yang salah dsb..


## Desktop Browser Testing

Buka Command Prompt di root folder project ini.
```sh
$ ionic serve
```

Metode testing lainnya bisa dibaca di:
https://ionicframework.com/docs/v1/guide/testing.html

## E-Book Source ( Tutorial Ionic dan Firebase )

https://javebratt.com/wp-content/uploads/2018/01/first-ionic-firebase-app-1.0.5.pdf
