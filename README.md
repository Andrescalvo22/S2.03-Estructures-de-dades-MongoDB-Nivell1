📄 **Description**

This project manages clients, suppliers, eyeglasses, and sales for the optical store "Cul d'Ampolla".  
It tracks suppliers' contact info, eyeglass details (brand, prescription, frame type/color, lens color, price), client info (including who recommended them), and records which employee sold each pair of glasses and when.  
A **Draw.io diagram** is included to illustrate the connections and relationships between the collections.

---

💻 **Technologies Used**

- MongoDB (Compass or shell)
- JSON (for collection export/import)
- Draw.io (for entity-relationship diagram)

---

📋 **Requirements**

- MongoDB 4.0+  
- Exported JSON collections: suppliers, glasses, clients, sales

  ---

🛠️ **Installation**

1. Clone the repository:  
   ```bash
   git clone <your-repo-url>

2. Navigate to the project folder:
   ```bash
    cd <project-folder>
3.Import the collections into MongoDB
```bash
mongoimport --db optics --collection suppliers --file suppliers.json --jsonArray
mongoimport --db optics --collection glasses --file glasses.json --jsonArray
mongoimport --db optics --collection clients --file clients.json --jsonArray
mongoimport --db optics --collection sales --file sales.json --jsonArray

```
---

▶️ **Execution**

-Open MongoDB Compass or the MongoDB shell and explore/manage the collections.

🌐 **Deployment**

-Mainly for learning purposes. For production, ensure MongoDB is running and accessible.

📂 **Draw.io Diagram**

-The repository includes a Draw.io diagram file (diagram.drawio) showing the relationships between collections.

🤝 **Contributions**

-Fork the repo, make improvements, and submit a pull request.

-Keep collections and data organized and documented.


