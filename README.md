## Install Requirements.txt

```
pip install pipreqs
pipreqs .

# tambahkan opsi --force jika sudah terdapat berkas requirements.txt
pipreqs --force

# tambahkan opsi --print jika hanya ingin menampilkan sebagai output
# tanpa menghasilkan berkas requirements.txt
pipreqs --print

# tambahkan opsi --scan-notebooks supaya bisa mendeteksi .ipynb
# tanpa option ini, tidak akan mendeteksi berkas notebook
pipreqs --scan-notebooks

# tambahkan opsi --ignore <dirs> supaya package melewatkan pengecekan
# pada direktori terkait
pipreqs --ignore env
```

## Run steamlit app:

```
streamlit run dashboard/dashboard.py
```
