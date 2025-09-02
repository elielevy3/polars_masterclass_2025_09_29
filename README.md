# Polars Masterclass 🐻‍❄️⚡

A hands-on masterclass on [Polars](https://pola.rs/), the fast DataFrame library for Python and Rust.  
This environment is fully containerized with **Docker** for a smooth and reproducible setup.  

---

## 📦 Features

- Pre-configured **Docker** environment  
- **Jupyter Notebook/Lab** for interactive exploration  
- **Ready-to-use** datasets & examples  
- No local dependency issues 🚀  

---

## 🛠️ Requirements

- Have docker installed on your machine (install guide [here](https://docs.docker.com/desktop/setup/install/mac-install/)) 🐋

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone git@github.com:elielevy3/polars_masterclass_2025_09_29.git
```

### 2. Launch docker

- Run docker desktop
- If using docker deamon from terminal:
```bash
dockerd
```

### 3. Build image (at the Dockerfile level)
```bash
docker build -t polars-app .
```

### 4. Run container (where your data files will be located)
```bash
docker run -it --rm -p 8888:8888 -v $(pwd):/app polars-app
```

### 5. Launch jupyter notebook

Click on the link to your localhost
<img width="1424" height="379" alt="Screenshot 2025-09-02 at 18 00 55" src="https://github.com/user-attachments/assets/9415708c-cb0a-493e-8552-221c94b86ee1" />

### 6. Run the first few cells to make sure everything works fine 

<img width="1201" height="483" alt="image" src="https://github.com/user-attachments/assets/3e7766b2-8adb-499f-8a31-2ad3f24c1904" />

