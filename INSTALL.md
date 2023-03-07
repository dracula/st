### [st](http://st.suckless.org/)

#### Activating theme

1. Download the latest version of st. You can check the latest version in
   [st's page](http://st.suckless.org/):

```
wget http://dl.suckless.org/st/st-0.9.tar.gz
```

2. Also download the latest dracula st patch version. You can check the latest
   version in [dracula patch's page](http://st.suckless.org/patches/dracula/):
   
```
wget http://st.suckless.org/patches/dracula/st-dracula-0.8.5.diff
```

3. Uncompress st file and get into the directory:

```
tar xf st-0.9.tar.gz
cd st-0.9/
```

4. Apply the patch, compile and install st:

```
patch -p1 < ../st-dracula-0.8.5.diff
make
sudo make install
```
