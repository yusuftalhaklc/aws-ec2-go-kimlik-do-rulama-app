curl -X POST http://ec2-54-158-63-47.compute-1.amazonaws.com:3000/verify \
-H "Content-Type: application/json" \
-d '{
  "TCKimlikNo": 12345678901,
  "Ad": "Ali",
  "Soyad": "Veli",
  "DogumYili": 1990
}'
