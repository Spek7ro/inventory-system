# inventory-system

### Prueba técnica: Desarrollo una API REST para gestionar el inventario de una cadena de tiendas minoristas. 

## 📁 Estructura del proyecto
```plaintext
inventory_system/
├── app/
│   ├── api/
│   │   ├── v1/
│   │   │   ├── endpoints/
│   │   │   │   ├── products.py
│   │   │   │   ├── inventory.py
│   │   │   │   └── transfer.py
│   │   │   └── router.py
│   ├── core/
│   │   ├── config.py
│   │   └── logging.py
│   ├── crud/
│   │   ├── product.py
│   │   ├── inventory.py
│   │   └── transfer.py
│   ├── db/
│   │   ├── base.py
│   │   ├── session.py
│   │   └── init_db.py
│   ├── models/
│   │   ├── product.py
│   │   ├── inventory.py
│   │   └── movement.py
│   ├── schemas/
│   │   ├── product.py
│   │   ├── inventory.py
│   │   └── movement.py
│   └── main.py
├── tests/
│   ├── unit/
│   └── integration/
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── README.md
```
## ⚙️ Configuración del Entorno


