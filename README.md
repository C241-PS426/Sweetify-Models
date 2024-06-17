# Sweetify Models
## Overview 
Selamat datang di repositori Sweetify-Models! Repositori ini berisi model Convolutional Neural Network (CNN) yang dikembangkan untuk project Sweetify.

## Deskripsi Project
Kami mengembangkan project bernama SWEETIFY, sebuah aplikasi yang bertujuan membantu pengguna memantau asupan gula dari minuman kemasan. Model yang terdapat di repositori ini digunakan untuk mengklasifikasikan gambar minuman kemasan ke dalam kategori gula yang sesuai (A-D). Aplikasi ini akan memberikan informasi mengenai kandungan gula dalam minuman kemasan, tracking dan menganalisis asupan gula harian pengguna, serta memberikan rekomendasi dan tips dalam menerapkan gaya hidup sehat untuk mengurangi risiko obesitas dan diabetes.

## Dataset
Dataset ini dikumpulkan untuk memprediksi kadar gula pada minuman berdasarkan sistem Grade (A-D). Kami mengumpulkan data gambar sebanyak 3000++ dengan 75 kelas yang masing-masing kelas terdapat 50 gambar.

## Kelas-kelas pada Dataset
| No | Produk                                | Gula/Sajian (g) | Takaran Saji (ml) | Gula/100ml (g) | Grade |
|----|----------------------------------------|-----------------|-------------------|----------------|-------|
| 1  | Lemon Water                           | 37              | 500               | 7.400          | C     |
| 2  | Ion Water                             | 9               | 250               | 3.600          | B     |
| 3  | C1000 Vitamin Apple                   | 14              | 140               | 10.000         | C     |
| 4  | C1000 Vitamin Lemon                   | 16              | 140               | 11.429         | D     |
| 5  | C1000 Vitamin Orange                  | 20              | 140               | 14.286         | D     |
| 6  | Hydro Coco                            | 7               | 250               | 2.800          | B     |
| 7  | Vita D                                | 9               | 330               | 2.727          | B     |
| 8  | Hemaviton C1000 Orange                | 20              | 330               | 6.061          | D     |
| 9  | Hemaviton C1000 Lemon                 | 16              | 330               | 4.848          | D     |
| 10 | Hemaviton C1000 Less Sugar            | 13              | 330               | 3.939          | C     |
| 11 | Bear Band Gold                        | 9               | 140               | 6.429          | C     |
| 12 | Bear Band                             | 9               | 189               | 4.762          | B     |
| 13 | Indomilk Susu Steril Plain            | 8               | 189               | 4.233          | B     |
| 14 | Indomilk Susu Steril Honey            | 19              | 189               | 10.053         | C     |
| 15 | Goodnes Kurma Royale                  | 20              | 189               | 10.582         | D     |
| 16 | Tujuh Kurma                           | 19              | 189               | 10.053         | C     |
| 17 | Entrasol                              | 9               | 180               | 5.000          | B     |
| 18 | Ultramilk Moka                        | 13              | 200               | 6.500          | C     |
| 19 | Ultramilk Strowberi                   | 19              | 200               | 9.500          | C     |
| 20 | Ultramilk Full Cream                  | 8               | 200               | 4.000          | B     |
| 21 | Frisian Flag Low Fat Belgian          | 21              | 225               | 9.333          | C     |
| 22 | Frisian Flag Coconut                  | 16              | 225               | 7.111          | C     |
| 23 | Frisian Flag Swiss Chocolate          | 20              | 225               | 8.889          | C     |
| 24 | Frisian Flag Strawberry               | 22              | 225               | 9.778          | C     |
| 25 | Frisian Flag Full Cream               | 10              | 225               | 4.444          | B     |
| 26 | Frisian Flag Susu Sereal Cokelat      | 12              | 225               | 5.333          | C     |
| 27 | Frisian Flag Susu Sereal Kopi         | 19              | 225               | 8.444          | C     |
| 28 | Cimory Marie Biscuits                 | 9               | 125               | 7.200          | C     |
| 29 | Cimory Hazelnut                       | 10              | 125               | 8.000          | C     |
| 30 | Cimory Cashew                         | 10              | 125               | 8.000          | C     |
| 31 | Cimory Chocolate                      | 10              | 125               | 8.000          | C     |
| 32 | Cimory Choco Malt                     | 10              | 125               | 8.000          | C     |
| 33 | Cimory Chocolate Tiramisu             | 12              | 125               | 9.600          | C     |
| 34 | Cimory Chocolate Mint                 | 12              | 125               | 9.600          | C     |
| 35 | Cimory Strawberry                     | 9               | 125               | 7.200          | C     |
| 36 | Ultramilk Karamel                     | 11              | 200               | 5.500          | C     |
| 37 | Ultramilk Taro                        | 14              | 200               | 7.000          | C     |
| 38 | Milo                                  | 15              | 180               | 8.333          | C     |
| 39 | Milo Nutriactive Choco Banana Multigrain | 15            | 180               | 8.333          | C     |
| 40 | Ultramilk Low Fat Cokelat             | 21              | 200               | 10.500         | D     |
| 41 | Ultramilk Low Fat                     | 9               | 200               | 4.500          | B     |
| 42 | Teh Botol Less Sugar                  | 11              | 225               | 4.889          | B     |
| 43 | Teh Pucuk Less Sugar                  | 12              | 240               | 5.000          | B     |
| 44 | Teh Botol Original                    | 16              | 225               | 7.111          | C     |
| 45 | Nu Choco Hazeltea                     | 17              | 200               | 8.500          | C     |
| 46 | Nu Milk Tea                           | 16              | 200               | 8.000          | C     |
| 47 | Nu Green Tea Madu                     | 18              | 200               | 9.000          | C     |
| 48 | Nu Green Tea                          | 16              | 200               | 8.000          | C     |
| 49 | Teh Kotak Less Sugar                  | 11              | 200               | 5.500          | C     |
| 50 | Fruit Tea Blackcurrant                | 22              | 250               | 8.800          | C     |
| 51 | Fruit Tea Lemon                       | 23              | 250               | 9.200          | C     |
| 52 | Fruit Tea Freeze                      | 22              | 250               | 8.800          | C     |
| 53 | Fruit Tea Strawberry                  | 22              | 250               | 8.800          | C     |
| 54 | Fruit Tea Apel                        | 22              | 250               | 8.800          | C     |
| 55 | Kopiko 78c                            | 20              | 240               | 8.333          | C     |
| 56 | Good Day Funtastic Mocacinno          | 22              | 250               | 8.800          | C     |
| 57 | Good Day Avocado Delight              | 23              | 250               | 9.200          | C     |
| 58 | Nescafe Latte                         | 17              | 220               | 7.727          | C     |
| 59 | Nescafe Mocha                         | 22              | 220               | 10.000         | C     |
| 60 | Nescafe Original                      | 17              | 220               | 7.727          | C     |
| 61 | Coca Cola Limited Edition             | 0               | 225               | 0.000          | A     |
| 62 | Nu Yogurt Tea                         | 20              | 200               | 10.000         | C     |
| 63 | Teh Kotak Lemon                       | 20              | 200               | 10.000         | C     |
| 64 | Teh Kotak Melati                      | 17              | 200               | 8.500          | C     |
| 65 | Nipis Madu                            | 22              | 240               | 9.167          | C     |
| 66 | Ultramilk Coklat                      | 19              | 200               | 9.500          | C     |
| 67 | Sari Kacang Ijo                       | 20              | 200               | 10.000         | C     |
| 68 | Teh Pucuk Harum                       | 18              | 240               | 7.500          | C     |
| 69 | Frestea Madu                          | 21              | 250               | 8.400          | C     |
| 70 | Pocarie Sweat                         | 14              | 250               | 5.600          | C     |
| 71 | Isoplus                               | 23              | 350               | 6.571          | C     |
| 72 | Orange Water                          | 40              | 500               | 8.000          | C     |
| 73 | Fanta                                 | 12              | 250               | 4.800          | B     |
| 74 | Coca Cola                             | 27              | 250               | 10.800         | D     |
| 75 | Sprite                                | 12              | 250               | 4.800          | B     |
