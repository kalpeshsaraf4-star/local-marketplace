<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Local Business & Community Services</title>
  <style>
    body{margin:0;font-family:Arial,sans-serif;background:#f1f3f6}
    header{background:#2874f0;color:#fff;padding:15px;text-align:center}
    .container{width:90%;max-width:1200px;margin:auto;padding:20px}
    .search{background:#fff;padding:10px;border-radius:8px;margin:15px 0}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:15px}
    .card,.box{background:#fff;border-radius:10px;padding:15px;box-shadow:0 2px 8px rgba(0,0,0,.08)}
    .card h3{margin:0 0 8px}
    button{background:#fb641b;color:#fff;border:none;padding:8px 12px;border-radius:6px;cursor:pointer}
    input,textarea,select{width:100%;padding:10px;margin:6px 0;border:1px solid #ccc;border-radius:6px}
    .row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .small{font-size:14px;color:#555}
    pre{background:#f8f8f8;padding:12px;border-radius:8px;overflow:auto}
    @media(max-width:700px){.row{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <h1>Local Business & Community Services</h1>
    <p>Flipkart Style Mini Marketplace</p>
  </header>

  <div class="container">
    <div class="box">
      <h2>Shop Owner Details</h2>
      <p><b>Fresh Mart Grocery</b><br>Owner: Ramesh Patel<br>Contact: 9876510001<br>Address: 12 Market Road, City Center</p>
      <p><b>Style Walk Shoes</b><br>Owner: Meena Sharma<br>Contact: 9876510002<br>Address: 28 Station Lane</p>
      <p><b>Royal Time Watches</b><br>Owner: Arif Khan<br>Contact: 9876510003<br>Address: 4 Clock Tower Plaza</p>
      <p><b>Beauty & Daily Needs</b><br>Owner: Sunita Verma<br>Contact: 9876510004<br>Address: Community Shopping Complex</p>
    </div>

    <div class="box">
      <h2>Products</h2>
      <div class="grid" id="productList"></div>
    </div>

    <div class="box">
      <h2>Add To Cart</h2>
      <div id="cartItems"></div>
      <h3>Total: Rs <span id="total">0</span></h3>
    </div>

    <div class="box">
      <h2>Customer Details</h2>
      <div class="row">
        <div><input id="custName" placeholder="Customer Name"></div>
        <div><input id="custPhone" placeholder="Customer Phone"></div>
      </div>
      <textarea id="custAddress" placeholder="Customer Delivery Address"></textarea>
      <select id="payment">
        <option>Cash on Delivery</option>
        <option>UPI</option>
        <option>Card</option>
      </select>
      <button onclick="placeOrder()">Place Order</button>
      <p id="status" class="small"></p>
    </div>

    <div class="box">
      <h2>ER Diagram</h2>
      <pre>
ShopOwner(owner_id, owner_name, contact_no, address)
Shop(shop_id, owner_id, shop_name, category)
Product(product_id, shop_id, product_name, category, price)
Customer(customer_id, customer_name, phone, address)
Cart(cart_id, customer_id, product_id, quantity)
Order(order_id, customer_id, total_amount, payment_method)
Shipping(shipping_id, order_id, delivery_address, status)
      </pre>
    </div>
  </div>

  <script>
    const products = [
      {id:1,name:"Grocery Food Pack",cat:"Grocery Food Items",price:500,owner:"Ramesh Patel",phone:"9876510001"},
      {id:2,name:"Running Shoes",cat:"Shoes",price:1200,owner:"Meena Sharma",phone:"9876510002"},
      {id:3,name:"Wrist Watch",cat:"Watches",price:1800,owner:"Arif Khan",phone:"9876510003"},
      {id:4,name:"Hand Bag",cat:"Bags",price:900,owner:"Neha Joshi",phone:"9876510005"},
      {id:5,name:"Jewellery Set",cat:"Jewellery",price:2200,owner:"Pooja Agarwal",phone:"9876510006"},
      {id:6,name:"Cosmetic Kit",cat:"Cosmetics",price:700,owner:"Sunita Verma",phone:"9876510004"},
      {id:7,name:"Soap Pack",cat:"Soaps",price:150,owner:"Vikram Saini",phone:"9876510007"},
      {id:8,name:"Daily Use Combo",cat:"Ladies & Gents Daily Use Items",price:600,owner:"Kiran Gupta",phone:"9876510008"}
    ];

    let cart = [];

    function showProducts() {
      document.getElementById("productList").innerHTML = products.map(p => `
        <div class="card">
          <h3>${p.name}</h3>
          <p>${p.cat}</p>
          <p>Price: Rs ${p.price}</p>
          <p>Owner: ${p.owner}</p>
          <p>Contact: ${p.phone}</p>
          <button onclick="addToCart(${p.id})">Add To Cart</button>
        </div>
      `).join("");
    }

    function addToCart(id) {
      let item = cart.find(x => x.id === id);
      let p = products.find(x => x.id === id);
      if (item) item.qty++;
      else cart.push({...p, qty:1});
      showCart();
    }

    function showCart() {
      document.getElementById("cartItems").innerHTML =
        cart.length
          ? cart.map(i => `<p>${i.name} x ${i.qty} = Rs ${i.price * i.qty}</p>`).join("")
          : "Cart is empty";

      document.getElementById("total").innerText =
        cart.reduce((sum, item) => sum + item.price * item.qty, 0);
    }

    function placeOrder() {
      const name = document.getElementById("custName").value;
      const phone = document.getElementById("custPhone").value;
      const address = document.getElementById("custAddress").value;
      const payment = document.getElementById("payment").value;

      if (!name || !phone || !address || cart.length === 0) {
        document.getElementById("status").innerText =
          "Please fill customer details and add products to cart.";
        return;
      }

      document.getElementById("status").innerHTML =
        "<b>Order Placed Successfully</b><br>" +
        "Shipping Status: Shipped<br>" +
        "Delivered On Address: " + address + "<br>" +
        "Payment Method: " + payment;

      cart = [];
      showCart();
    }

    showProducts();
    showCart();
  </script>
</body>
</html>
