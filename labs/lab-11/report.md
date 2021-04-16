## Checkpoint 1

![Screenshot](screenshots/1.png)

## Checkpoint 2

Modified code:
```
num_rows = 5
num_cols = 3
num_images = num_rows*num_cols
plt.figure(figsize=(2*2*num_cols, 2*num_rows))
for i in range(num_images):
  plt.subplot(num_rows, 2*num_cols, 2*i+1)
  plot_image(i+9000, predictions[i+9000], test_labels, test_images)
  plt.subplot(num_rows, 2*num_cols, 2*i+2)
  plot_value_array(i+9000, predictions[i+9000], test_labels)
plt.tight_layout()
plt.show()
```

Screenshot:
![Screenshot](screenshots/2.png)

## Checkpoint 3

Original 1:
![Original 1](https://12ax7web.s3.amazonaws.com/accounts/1/products/1986199879943/Ramen-Panda-tahiti-blue-light-t-shirt-teeturtle-full-21-1000x1000.jpg)
Converted 1:
![Converted 1](1out.jpg)

![Original 2](https://ae01.alicdn.com/kf/H578ae5e36bde4eed97f507afb55e17f5Z/2020-New-Waterproof-Winter-Jacket-Men-Hoodied-Parka-Men-Warm-Winter-Coat-Men-Thicken-Zipper-Camouflage.jpg_Q90.jpg_.webp)
Converted 2:
![Converted 2](2out.jpg)

![Original 3](https://media.gq-magazine.co.uk/photos/5f3a8deeffe32218efca5004/master/w_1000,c_limit/20200817-jeans-04.jpg)
Converted 3:
![Converted 3](3out.jpg)
