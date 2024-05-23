---
title: Ecovim, neovim boilerplate setup
description:
  Sebagai pengguna awam untuk Neovim, memakai boilerplate seperti Ecovim atau LazyVim merupakan kebutuhan. Kita tidak perlu memakukan config Neovim dari awal
  dan lebih berfokus untuk melatih muscle memory kita.
tags:
  - neovim
---

Sudah hampir 7 tahun saya mengenal dunia VIM. Tapi seperti halnya toxic relationship dalam dunia percintaan, VIM bukan
satu-satunya IDE atau Code Editor yang pernah saya gunakan. Ada kecenderungan saya untuk melakukan suatu hal yang menantang,
atau kata orang learn the hard way. Dulu waktu saya sering bermain dota, saya suka sekali bermain Invoker, Pudge atau Chen yang merupakan
hero dengan kebutuhan microskill yang baik. Untuk urusan IDE ini, saya berpindah-pindah antara VIM dan VSCode. Pernah juga sesekali
memakai produk berbayar Jetbrain untuk mengetahui pengalamannya. Sayangnya sampai sekarang walaupun saya masih memakai Neovim, saya
belum sejago para programmer di Youtube atau social media, saya juga tidak berpikir bahwa VIM/Neovim dapat meningkatkan produktivitas
dari programmer. Banyak programmer yang sangat produktif dengan VSCode, Atom, Sublime atau Emacs.

Untuk saat ini, saya memakai Neovim dengan boilerplate dari [Ecovim](https://github.com/ecosse3/nvim). Saya coba dengan kebutuhan
config yang minimal, tidak banyak melakukan customize karena dulu sekali saya sering keasyikan menghabiskan waktu merubah-ubah vim config sampai lupa waktu.
Bisa dilihat bahwa stack saya untuk coding cuman memakai neovim, tmux dan ohmyzsh.
perubahan untuk ecovim.![default stack](/attachments/ecovim.png)

Beberapa hal yang saya suka dari Ecovim adalah sebagai berikut:

- Plugin lebih sederhana daripada [LazyVim](https://github.com/LazyVim/LazyVim)
- Dalam 6 bulan terakhir saya lebih banyak mengerjakan Frontend, karena itu sangat cocok dengan beberapa config dari Ecovim.
- Sudah terintegrasi [Mason](https://github.com/williamboman/mason.nvim), sangat mudah menginsall plugins sesuai kebutuhan.
- Keymapping bawaan relatif lebih sederhana.
