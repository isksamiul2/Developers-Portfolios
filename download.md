# 📥 How to Download a Contributor's Portfolio Source Code

If you want to download the source code of a particular contributor's portfolio from this repository, follow these steps:

## 🔹 Method 1: Download as a ZIP File
1. **Go to the repository**: [Developers-Portfolios](https://github.com/ksamiul/Developers-Portfolios)
2. Navigate to the `Portfolios/` folder.
3. Locate the contributor's portfolio folder (e.g., `Portfolios/contributor1`).
4. Click on the folder to open it.
5. Click on the **“Download ZIP”** button (top right corner) to download the entire folder.
6. Extract the ZIP file to access the source code.

---

## 🔹 Method 2: Using Git with Sparse Checkout
If you only need a specific contributor’s portfolio and don’t want to clone the entire repository, use Git’s sparse checkout feature:

```sh
git clone --no-checkout https://github.com/ksamiul/Developers-Portfolios.git
cd Developers-Portfolios
git sparse-checkout init --cone
git sparse-checkout set Portfolios/contributor1
git checkout
```

Replace `contributor1` with the GitHub username or folder name you want to download.

---

## 🔹 Method 3: Clone the Entire Repository
If you want all contributors' portfolios, clone the full repository:
```sh
git clone https://github.com/ksamiul/Developers-Portfolios.git
```
Navigate into the folder:
```sh
cd Developers-Portfolios/Portfolios
```
Now, you can access all contributors' portfolios.

---

## ℹ️ Need Help?
If you face any issues while downloading, feel free to open an **issue** in the repository or reach out for support.

Happy Coding! 🚀

