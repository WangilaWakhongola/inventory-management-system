\# Inventory Management System



A Flask-based web application for managing product inventory with real-time tracking and analytics.



\## Features



\- ✅ Add, edit, delete, and view products

\- ✅ Real-time stock level monitoring

\- ✅ Low stock alerts

\- ✅ Search and filter products

\- ✅ Inventory statistics dashboard

\- ✅ RESTful API endpoints

\- ✅ SQLite database integration



\## Requirements



\- Python 3.8+

\- Flask 2.3.3

\- Flask-SQLAlchemy 3.0.5



\## Installation \& Setup



1\. \*\*Clone the repository:\*\*

```bash

git clone https://github.com/YOUR\_USERNAME/inventory-management-system.git

cd inventory-management-system

```



2\. \*\*Create virtual environment:\*\*

```bash

python -m venv venv

source venv/bin/activate  # On Windows: venv\\Scripts\\activate

```



3\. \*\*Install dependencies:\*\*

```bash

pip install -r requirements.txt

```



4\. \*\*Run the application:\*\*

```bash

python app.py

```



5\. \*\*Open in browser:\*\*

Navigate to `http://localhost:5000`



\## API Endpoints



\- `GET /` - Dashboard

\- `GET /api/products` - Get all products

\- `POST /api/products` - Create product

\- `GET /api/products/<id>` - Get specific product

\- `PUT /api/products/<id>` - Update product

\- `DELETE /api/products/<id>` - Delete product

\- `GET /api/products/search` - Search products

\- `GET /api/stats` - Get statistics



\## Project Structure



```

inventory-management-system/

├── app.py                    # Main Flask application

├── requirements.txt          # Python dependencies

├── README.md                # Project documentation

├── .gitignore              # Git ignore rules

├── templates/

│   └── index.html          # Frontend HTML template

└── static/

&nbsp;   ├── css/

&nbsp;   │   └── style.css       # Styling

&nbsp;   └── js/

&nbsp;       └── script.js       # Frontend JavaScript

```



\## Features Explained



&nbsp;Dashboard Stats

\- Real-time total product count

\- Total inventory value

\- Low stock item alerts



&nbsp;Product Management

\- Add new products with details

\- Edit existing products

\- Delete products

\- Search by product name or description

\- Filter by category



\### Automatic Calculations

\- Total value calculation (quantity × price)

\- Low stock status based on reorder level

\- Category management



\## Usage



\### Adding a Product

1\. Fill in the "Add New Product" form

2\. Enter product name, category, quantity, price

3\. Set reorder level (optional)

4\. Click "Add Product"



\### Editing a Product

1\. Click "Edit" button next to product

2\. Modify product details

3\. Click "Save Changes"



\### Deleting a Product

1\. Click "Delete" button next to product

2\. Confirm deletion



&nbsp;Searching Products

1\. Use search box to find by name

2\. Use category filter to filter by type



Future Enhancements



\- User authentication \& authorization

\- Product images

\- Inventory history tracking

\- Advanced analytics \& reporting

\- Barcode scanning

\- Multi-warehouse support



&nbsp;Author



Emmanuel Wakhongola



&nbsp;Contact



Email: wangilaemmanuel06@gmail.com



License



MIT License

"# Inventory-Management-System" 
