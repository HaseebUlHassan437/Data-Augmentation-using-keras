# 📸 Data Augmentation using Keras

This notebook demonstrates how to perform image data augmentation using **Keras** in a Google Colab environment. The purpose of this augmentation is to artificially increase the size and diversity of image datasets for better generalization in deep learning models.

---

## 📘 Concepts Covered

### 🔁 What is Data Augmentation?
Data augmentation is a technique used to create new training examples from existing images by applying random transformations such as:
- Rotation
- Zoom
- Translation (shift)
- Shear
- Horizontal Flip

This increases dataset size and helps reduce overfitting in deep learning models.

---

### 🛠️ Tools Used
- **Keras ImageDataGenerator** for augmentation
- **Google Colab** for execution
- **Matplotlib** and **PIL** for image visualization
- **Google Drive** for image access and persistence

---

## 🧪 Notebook Workflow

1. **Mount Google Drive** to access image assets
2. **Read an image** from a specified Drive path
3. **Apply Keras-based transformations** (excluding vertical flip)
4. **Generate and save 10 augmented images**
5. **Visualize original and augmented images**

---

## 🖼️ Example Augmentation Techniques Used
- `rotation_range=40`
- `width_shift_range=0.2`
- `height_shift_range=0.2`
- `shear_range=0.2`
- `zoom_range=0.2`
- `horizontal_flip=True`
- `vertical_flip=False`

These ensure that the data remains realistic (e.g., a cat shouldn't be upside-down!) while enhancing diversity.

---

## 📂 Output
- Augmented images are saved in `/content/augmented_images/`
- Visual grid output of the 10 generated images

---

## 📌 Usage
To run this notebook:
1. Upload your image to Google Drive
2. Replace the `image_path` in the notebook
3. Run each cell in order
4. View and save augmented results

---

## 👨‍💻 Author
**Haseeb Ul Hassan**  
[GitHub Profile](https://github.com/HaseebUlHassan437)


