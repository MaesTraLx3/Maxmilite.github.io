**You could add these three lines to the `hosts` file in the `%systemroot%/system32/drivers/etc` folder:**

```
140.82.114.4 github.com
185.199.108.153 assets-cdn.github.com
199.232.69.194 github.global.ssl.fastly.net
```

After that, you can launch the terminal and input this command:

```
ipconfig /flushdns
```