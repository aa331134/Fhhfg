/* إعدادات أساسية */
body {
  background-color: #f3f4f6;
  font-family: 'Tahoma', sans-serif;
  padding: 20px;
  direction: rtl;
}

/* العناوين */
h1 {
  text-align: center;
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}

h2 {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 15px;
}

/* الحاويات */
.container {
  max-width: 1000px;
  margin: auto;
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  margin-bottom: 30px;
}

/* أزرار */
button {
  padding: 10px 20px;
  border: none;
  border-radius: 6px;
  color: white;
  cursor: pointer;
  font-size: 16px;
  margin-top: 10px;
}

button:hover {
  opacity: 0.9;
}

.bg-green {
  background-color: #16a34a;
}

.bg-blue {
  background-color: #2563eb;
}

.bg-indigo {
  background-color: #4f46e5;
}

/* الحقول */
input[type="text"],
input[type="number"] {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 6px;
  width: 100%;
  box-sizing: border-box;
  margin-bottom: 10px;
}

/* الجدول */
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 10px;
}

thead {
  background-color: #e5e7eb;
}

th, td {
  padding: 10px;
  border: 1px solid #ddd;
  text-align: right;
}

tfoot td {
  font-weight: bold;
}

/* حذف عند الطباعة */
@media print {
  button, #scanner, #scannerAdd {
    display: none !important;
  }
}
