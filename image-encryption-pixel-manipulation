## Task 2: Image Encryption (Pixel Manipulation)

### `image_encrypt.py`

```python
from PIL import Image

image = Image.open("input.jpg")
pixels = image.load()

for i in range(image.size[0]):
    for j in range(image.size[1]):
        r, g, b = pixels[i, j]
        pixels[i, j] = (255-r, 255-g, 255-b)

image.save("encrypted.jpg")
print("Encrypted image saved as encrypted.jpg")
