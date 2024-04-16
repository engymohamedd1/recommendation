# Example Request

curl -X POST -F "file=@C:\Users\Dell\PycharmProjects\pythonProject\downloaded_images\image_16.jpg" http://localhost:5000/recommend

# Response:
```
{
  "recommendations": [
    "downloaded_images\\image_16.jpg",
    "downloaded_images\\image_142.jpg",
    "downloaded_images\\image_140.jpg",
    "downloaded_images\\product_COOLMAX\u00ae Regular Fit T-shirt_0.jpg",
    "downloaded_images\\product_Regular Fit Pima Cotton Polo Shirt_0.jpg",
    "downloaded_images\\image_12.jpg"
  ]
}
```

# How to run this project 
python main.py
