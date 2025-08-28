# GWU CS6365 - Advanced Machine Learning

**Course Numbers:** CSCI-4907-87 / CSCI-6365-80  
**Alternative Name:** Advanced Topics Computer Science

This repository contains executable Jupyter notebook lectures for CS6365 Advanced Machine Learning at The George Washington University (Fall 2025 edition).

## 📋 Course Information

For detailed course information including schedule, grading, and policies, please see [SYLLABUS.md](SYLLABUS.md).

## 📁 Repository Structure

```
.
├── README.md              # Setup instructions (this file)
├── SYLLABUS.md           # Complete course syllabus  
├── requirements.txt      # Python packages for pip
├── requirements.yml      # Python packages for conda
└── slides/
    ├── lecture-1-introduction-to-graphs.ipynb
    └── img/              # Images and figures used in lectures
```

## 🚀 Environment Setup

You have two options to set up your environment: **Anaconda** (recommended) or **virtualenv**.

### Option 1: Anaconda (Recommended)

1. **Install Anaconda** if you haven't already:
   - Download from [https://www.anaconda.com/download](https://www.anaconda.com/download)

2. **Create and activate the environment**:
   ```bash
   conda create --name gw-cs6365 --file requirements.yml
   conda activate gw-cs6365
   ```

3. **Install Jupyter kernel**:
   ```bash
   python -m ipykernel install --user --name=gw-cs6365
   ```

4. **Start Jupyter Lab/Notebook**:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

### Option 2: Virtual Environment

1. **Create and activate virtual environment**:
   ```bash
   python -m venv gw-cs6365
   source gw-cs6365/bin/activate  # On Windows: gw-cs6365\Scripts\activate
   ```

2. **Install packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Install Jupyter kernel**:
   ```bash
   python -m ipykernel install --user --name=gw-cs6365
   ```

4. **Start Jupyter Lab/Notebook**:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

## 📖 Running the Lectures

1. **Open Jupyter** using one of the methods above
2. **Navigate** to the `slides/` directory
3. **Select the kernel**: When opening a notebook, make sure to select the `gw-cs6365` kernel
4. **Run the cells**: Execute cells sequentially using `Shift+Enter`

## 🛠️ Troubleshooting

### Common Issues

**"Kernel not found" error:**
- Make sure you installed the Jupyter kernel: `python -m ipykernel install --user --name=gw-cs6365`
- Restart Jupyter and select the correct kernel

**Missing packages:**
- Activate your environment first: `conda activate gw-cs6365` or `source gw-cs6365/bin/activate`
- Reinstall requirements: `pip install -r requirements.txt`

**Images not displaying:**
- Ensure you're running Jupyter from the repository root directory
- Check that the `slides/img/` directory contains all necessary files

### Getting Help

1. Check the [course syllabus](SYLLABUS.md) for contact information
2. Ask questions during class or office hours
3. Post on the course discussion forum

## 🎯 Quick Start Checklist

- [ ] Clone/download the repository
- [ ] Set up your environment (conda or virtualenv)
- [ ] Install the Jupyter kernel
- [ ] Start Jupyter Lab/Notebook
- [ ] Open a lecture notebook
- [ ] Select the `gw-cs6365` kernel
- [ ] Run the first cell to test everything works

## 📚 Credits

Course materials are adapted from multiple sources including:
- The ML course by Xavier Amatriain at SPHERE
- Stanford CS224W (https://web.stanford.edu/class/cs224w/)
- Poolparty Graph Academy (https://www.poolparty.biz/academy)