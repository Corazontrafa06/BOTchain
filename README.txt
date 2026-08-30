BOT Chain Community PFP
=======================

Folder web yang dipakai: botchain-pfp
Jalur file storage baru: botchain/  (di dalam bucket botchain_pfp)

Yang sudah diganti
------------------
- Tema visual: hitam + hijau BOT Chain
- Logo & background: assets/logo.jpg + assets/hero.jpg
- Network: BOT Chain Testnet
    Chain ID : 968
    RPC      : https://rpc.bohr.life
    Explorer : https://scan.bohr.life
    Token    : BOT
    Faucet   : https://faucet.botchain.ai
- Wallet penerima bayaran / admin on-chain:
    0x3644fadb0A69EdEbEF64B0aBD71342335C5Aa7ee
- Biaya commission testnet: 1 BOT atau 0.1 BOT (native), plus opsi gratis
- Password admin: botchain123

Yang perlu kamu set di hosting / Supabase
-----------------------------------------
1. Upload seluruh folder botchain-pfp ke web (jaga struktur assets/).
2. Di Supabase Storage, buat bucket baru bernama:
      botchain_pfp
   Set Public.
3. Folder di dalam bucket akan terbentuk otomatis saat upload pertama:
      botchain/gallery/
      botchain/commission-ref/
      botchain/commission-final/
4. Tabel lama (pfps, commissions) masih dipakai.
5. NFT mint belum aktif sampai kontrak di-deploy ke BOT Chain Testnet.
   Setelah deploy, isi CONTRACT_ADDRESS di index.html.

Mainnet nanti (jangan dipakai dulu)
-----------------------------------
Chain ID : 677
RPC      : https://rpc.botchain.ai
Explorer : https://scan.botchain.ai
