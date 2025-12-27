# oh_my_cd

よく使うディレクトリへ素早く移動するための cd エイリアス集。
`cdd` (Documents), `cdp` (Pictures), `cdv` (Videos), `cdl` (Downloads) の4つのコマンドを提供します。

## 設定方法

### Linux / Mac

```bash
echo 'source ~/Documents/oh_my_cd/oh_my_cd.sh' >> ~/.bashrc
source ~/.bashrc
```

### Windows (PowerShell)

```powershell
echo '. ~\Documents\oh_my_cd\oh_my_cd.ps1' >> $PROFILE
. $PROFILE
```
