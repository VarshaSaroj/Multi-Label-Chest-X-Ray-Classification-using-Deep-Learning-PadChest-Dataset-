# 📁 PadChest Dataset – Access Instructions

> ⚠️ The **PadChest dataset is not included** in this repository due to its large size (~1 TB) and license restrictions.

---

## 🔗 Dataset Download

You can manually download the full dataset from the official B2DROP archive:

👉 [https://b2drop.bsc.es/index.php/s/BIMCV-PadChest-FULL](https://b2drop.bsc.es/index.php/s/BIMCV-PadChest-FULL)

---

## 📦 Contents

- 52 `.zip` files, each ~20 GB
- A metadata file:  
  `PADCHEST_chest_x_ray_images_labels_160K_01.02.19.csv.gz`

---

## 🛠️ How to Use

1. Visit the download page.
2. Download all `.zip` files and extract them locally.
3. Download and unzip the `csv.gz` file — it contains the labels and metadata.
4. Use the column `ImageID` to match image names and labels.
5. Load them in your Python notebooks using `pandas` or `numpy`.

---

## 📄 License Notice

- You **must not** share or publicly distribute the dataset.
- You **must** read and accept the license conditions on the [PadChest website](https://bimcv.cipf.es/bimcv-projects/padchest/).

---

## 📝 Tip:

Store the dataset in a local `data/` folder (which is `.gitignored`)  
You can mention in your notebook/code:
```python
data_path = "../data/images/"
