# Rustの実行環境を用意する

## Windowsの場合

- https://www.rust-lang.org/tools/install

から「DOWNLOAD RUSTUP-INIT.EXE(64-BIT)」を選択する。

ダウンロードされたインストーラを起動する。

```

The Cargo home directory located at:

  C:\Users\proje\.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  C:\Users\proje\.cargo\bin

This path will then be added to your PATH environment variable by
modifying the HKEY_CURRENT_USER/Environment/PATH registry key.

You can uninstall at any time with rustup self uninstall and
these changes will be reverted.

Current installation options:


   default host triple: x86_64-pc-windows-msvc
     default toolchain: stable (default)
               profile: default
  modify PATH variable: yes

1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
>1

info: profile set to 'default'
info: default host triple is x86_64-pc-windows-msvc
info: syncing channel updates for 'stable-x86_64-pc-windows-msvc'
info: latest update on 2022-02-24, rust version 1.59.0 (9d1b2106e 2022-02-23)
info: downloading component 'cargo'
info: downloading component 'clippy'
info: downloading component 'rust-docs'
 19.4 MiB /  19.4 MiB (100 %)   6.5 MiB/s in  3s ETA:  0s
info: downloading component 'rust-std'
 23.7 MiB /  23.7 MiB (100 %)   6.2 MiB/s in  3s ETA:  0s
info: downloading component 'rustc'
 55.6 MiB /  55.6 MiB (100 %)   6.7 MiB/s in  8s ETA:  0s
info: downloading component 'rustfmt'
info: installing component 'cargo'
info: installing component 'clippy'
info: installing component 'rust-docs'
 19.4 MiB /  19.4 MiB (100 %)   3.9 MiB/s in  4s ETA:  0s
info: installing component 'rust-std'
 23.7 MiB /  23.7 MiB (100 %)  13.5 MiB/s in  1s ETA:  0s
info: installing component 'rustc'
 55.6 MiB /  55.6 MiB (100 %)  13.0 MiB/s in  4s ETA:  0s
info: installing component 'rustfmt'
info: default toolchain set to 'stable-x86_64-pc-windows-msvc'

  stable-x86_64-pc-windows-msvc installed - rustc 1.59.0 (9d1b2106e 2022-02-23)


Rust is installed now. Great!

To get started you may need to restart your current shell.
This would reload its PATH environment variable to include
Cargo's bin directory (%USERPROFILE%\.cargo\bin).

Press the Enter key to continue.

```