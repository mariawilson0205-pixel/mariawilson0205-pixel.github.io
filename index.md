# Author Verification

This site lists official verification pages for my works.

## Official author key
- **Pen name:** Niw
- **PGP fingerprint:** '0797626D422661BC29E1EE794FFE36D44F92FE84'
- Download my public key: [**publickey.asc**](https://mariawilson0205-pixel.github.io/publickey.asc)

## Works
- [Pursuers & Coveteds (English, Part 1)](works/pursuers-coveteds-part-1/)

## How verification works (short)
Each work page lists one or more editions. For each edition, I publish:
- the **SHA-256** of the final PDF
- a **PGP-signed manifest** proving the hash was signed by my key

To verify:
1) Download `publickey.asc` and the edition’s `MANIFEST-*.txt.asc`
2) Run:
   - `gpg --import publickey.asc`
   - `gpg --verify MANIFEST-*.txt.asc`
3) Hash your PDF and compare the SHA-256.

