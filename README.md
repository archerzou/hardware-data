# hardware-data
## Deploy JSON Server to render.com

A template to deploy [JSON Server] allow you to run fake REST API online!

Demo from this repository: 

1. https://hardware-data.onrender.com
2. https://hardware-data.onrender.com/products

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into render.com.
4. From the webservice dashboard, click "**+ New Project**" then "**Import**" your repository.
5. Leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
 "products": [
    {
      "id": 1,
      "name": "Purple Hammer",
      "brand": "Cinncinnati Tools",
      "description": "This purple hammer hits nails harder than a hammer of any other color.",
      "retailPrice": 1045,
      "departmentId": 1
    },
  ],
 "departments": [
    {
      "id": 1,
      "name": "Hand Tools"
    },
  ],
  "checkout": []
}
```
