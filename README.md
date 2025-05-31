# esp-h2-dahu

installation de curl
sudo apt install curl

## Installation de RUST
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

rustup toolchain install nightly --component rust-src
rustup target add riscv32imac-unknown-none-elf

sudo apt update && sudo apt upgrade -y
sudo apt install -y wget software-properties-common gnupg
wget -O - https://apt.llvm.org/llvm-snapshot.gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/llvm-archive-keyring.gpg
sudo apt update
sudo apt install clang lld lldb

sudo apt-get install git wget flex bison gperf python3 python3-pip python3-venv cmake ninja-build ccache libffi-dev libssl-dev dfu-util libusb-1.0-0
cargo install ldproxy

cargo install esp-generate

esp-generate --chip=esp32h2 your-project

sudo apt update
sudo apt install libudev-dev
sudo apt install pkg-config
cargo install cargo-espflash
cargo install espflash

cargo install espup
espup install

sudo usermod -a -G dialout $USER
cargo run --release


  git config --global user.email "emmanuel.grandiere@laposte.net"
  git config --global user.name "dahu44"