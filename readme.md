# Face Recognition with and without mask

The project uses MTCNN for detecting faces, then applies a simple alignment for each detected face and feeds those aligned faces into embeddings model (Facenet). 
Finally, a softmax classifier and cosine similarity method was put on top of embedded vectors for classification task.
