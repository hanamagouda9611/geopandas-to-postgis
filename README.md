# 🗺️ Geopandas to PostGIS (Full CRUD Pipeline)

This project demonstrates how to perform full **CRUD (Create, Read, Update, Delete)** operations on spatial data using **GeoPandas**, **SQLAlchemy**, and **PostGIS** in a Jupyter Notebook.

GeoJSON files are loaded, visualized, stored in a PostgreSQL/PostGIS database, updated, queried, and finally cleaned up.

---
## 🚀 Features

- ✅ Automatically creates a PostgreSQL database
- ✅ Enables the PostGIS extension
- ✅ Reads GeoJSON spatial data using GeoPandas
- ✅ Load spatial data (GeoJSON) using GeoPandas
- ✅ Visualize spatial points
- ✅ Store data into a PostGIS-enabled PostgreSQL database
- ✅ Perform read and update operations
- ✅ Clean up by deleting tables and the database

## 🛠️ Requirements

- Python 3.8+
- PostgreSQL with PostGIS
- Required Python packages:
  - geopandas
  - sqlalchemy
  - psycopg2-binary
  - geoalchemy2
  - matplotlib (for plotting)

Install them using:

```bash
pip install geopandas sqlalchemy psycopg2-binary geoalchemy2 matplotlib
```
---
## ⚙️ Usage

1. Launch the Jupyter Notebook.

2. Replace the file path 'filepath/bengaluru.geojson' with the actual path to your GeoJSON file.

3. Run the notebook cells in order.

4. The script will:

    ! Create a database named bengaluruu
  
    !  Enable PostGIS
  
    ! Import your GeoJSON into a table called bengaluru_points
  
    ! Fetch and visualize the data
  
    ! Clean up (drop the table and database)
  
---
