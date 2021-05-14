# kivy_test
kivy-iosの練習

### Python仮想環境の構築
$python -m venv (仮想環境の名前)  
$source (仮想環境の名前)/bin/activate  

### パッケージのインストール
$pip install kivy-ios  
$brew install autoconf automake libtool pkg-config  
$brew link libtool  
$pip install cython


### Xcodeのエラー修正
$xcode-select --print-path  
(/Applications/Xcode.appになっていてほしい)  
$sudo xcode-select --switch /Applications/Xcode.app  
$xcrun -sdk iphonesimulator --show-sdk-path  
(何かパスが表示されればok)

### Python関係のモジュールをビルド
$toolchain build kivy