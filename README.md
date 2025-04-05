# GitKraKen-Crack
Works with the latest GitKraken (V11)

## Needed
- Node.js v16 or newer
- yarn
- GitKraKen v8.2.0 or newer

## GitKraken Download Link
[gitkraken](https://www.gitkraken.com/git-client/try-free)

## Crack Steps

### 1. Install Node, Gitkraken and Yarn
- npm install --global yarn

### 2. Clone this repo and run the Crack
- git clone https://github.com/qsshs/GitKraKen-Crack.git
- cd GitKraKen-Crack
- yarn install
- yarn build
- yarn gitcracken patcher

## Follow-up
### Block Updates
Add the following line at the bottom of the hosts file located at `C:\Windows\System32\drivers\etc`:
`127.0.0.1 release.gitkraken.com`
> Alternatively, you can delete the `update.exe` file in the `AppData/Local/gitkraken` directory to also prevent GitKraken from auto-updating.

### Launch from the actual software, not from the updater or installer
The real client executable is located at `AppData/Local/gitkraken/app-x/gitkraken.exe`.
