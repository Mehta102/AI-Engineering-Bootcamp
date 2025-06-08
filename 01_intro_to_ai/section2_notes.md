Section 2: Data in AI

Data is basically the fuel that powers everything in AI. Without good data, you can’t build reliable models — it’s as important as the algorithms themselves.

---

Types of Data

Structured Data
- Neatly organized into rows and columns (like Excel or databases).
- Easy to search, analyze, and feed into models.

Unstructured Data
- Messy, with no fixed format.
- Includes stuff like images, videos, audio, and plain text.
- Apparently, around 80–90% of all data out there is unstructured.

---

The MNIST Dataset (The “Hello World” of ML)

- Contains 70,000 grayscale images of handwritten digits (0–9).
- Each image is 28x28 pixels.
- Super common for testing and learning image classification.
- Good starting point for understanding how machines learn from image data.

---

How Images Are Represented Digitally

- Each pixel has a value between 0 (white) and 255 (black), with shades of gray in between.
- These pixel values are stored as binary numbers — just 0s and 1s.
- So an image is basically a big grid of numbers that the computer reads and learns from.

---

Learning to Recognize Digits

- The model looks at these pixel grids and learns to spot patterns (like how a “3” curves vs how a “9” loops).
- After training, it can look at a new image and predict which digit it is — simple but powerful intro to ML.

---

Human Perception vs Machine Learning

- Our brains are great at processing info from multiple senses all at once.
- AI tries to replicate this by learning from different data sources — images, text, sensor data, etc.
- Still a long way to go before it reaches our level of intuition, but it’s getting closer.

---

Why Data Quality Matters

- Models are only as good as the data we feed them. If the data is messy or inaccurate, the model’s output will be too.
- “Garbage in, garbage out” is a real thing.
- Good data can come from scraping websites, using APIs, or large-scale data pipelines.

---

Labeled vs Unlabeled Data

Labeled Data
- Every item is tagged (e.g., image labeled as “dog” or “not dog”, comment labeled as “positive”).
- Helps models learn specific categories or outcomes.
- More accurate, but also takes a lot of time and effort to label properly.

Unlabeled Data
- No labels — the model has to figure things out on its own.
- Useful when labeling everything manually would take forever.
- Cheaper, but usually less accurate unless combined with good techniques (like semi-supervised learning).

---

Metadata

- Metadata = “data about data”.
- Example: file size, file name, where it’s stored.
- Useful for organizing, filtering, and managing data more efficiently.

---

Overall takeaway: Clean, high-quality data (especially labeled data) makes a huge difference in how well an AI model performs.
