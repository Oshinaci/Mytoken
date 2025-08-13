MyToken adalah token crypto berbasis Ethereum yang memanfaatkan standar ERC20. Kontrak ini memungkinkan Anda untuk mencetak (mint) dan membakar (burn) token, serta mengelola pasokan token dengan mudah.

## Fitur
- **Standar ERC20**: Menggunakan implementasi ERC20 untuk kompatibilitas dengan ekosistem Ethereum.
- **Minting**: Pemilik kontrak dapat mencetak token baru.
- **Burning**: Pengguna dapat membakar token mereka sendiri.

## Instalasi
1. Clone repository ini: 
   ```bash
   git clone https://github.com/Oshinaci/mytoken.git
   cd mytoken
   ```
2. Pastikan Anda memiliki Node.js dan npm yang sudah terinstall.
3. Instal dependencies:
   ```bash
   npm install
   ```

## Penggunaan
1. Deploy kontrak menggunakan alat seperti [Hardhat](https://hardhat.org/) atau [Remix](https://remix.ethereum.org/).
2. Pastikan Anda memiliki saldo ETH untuk membayar gas fee.

## Contoh Deploy
Constructor memerlukan parameter berikut:
- `name`: Nama token (contoh: "MyToken").
- `symbol`: Simbol token (contoh: "MTK").
- `initialSupply`: Pasokan awal token (contoh: 1000000).

```solidity
constructor("MyToken", "MTK", 1000000);
```

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).
