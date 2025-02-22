body {
    font-family: "Roboto", sans-serif;
    margin: 0;
    padding: 0;
}

/* Navbar styling */
.navbar { 
    background-color: #c28e78;
    color: #ff0000;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1.5rem;
    padding: 1rem;
}
.navbar a {
    color: #fff;
    text-decoration: none;
    font-size: 16px;
    transition: color 0.3s;
}
.navbar a:hover {
    color: #fd0000;
}

/* Hero inage styling */
.hero-image-container { 
    width: 100%;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
}
.hero-image {
    width: 100%;
    height: auto;
}

/*Categories styling */
categories-container {
    text-align: left;
    padding: 2rem;
}

.categories-container h2 {
    margin-bottom: 1rem;
    font-size: 24px;
    color: #333;
}

.categories {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 0.5rem;
} 

.category {
    width: 200px;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 1rem;
    box-align: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
    background-color: #fff;
}

.product-image {
    width: 100%;
    height: auto;
    margin-bottom: 1rem;
    border-radius: 5px;
}

.category h3 {
    margin: 0.5rem 0;
    font-size: 16px;
    color: #333;
}

.category p {
    font-size: 14px;
    color: #666;
    margin: 0.5rem 0;
}

.add-to-cart {
    display: inline-block;
    padding: 0.5rem 1rem;
    font-size: 14px;
    color: #fff;
    background-color: #c28e78;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.add-to-cart:hover {
    background-color: #b27e63;
}

/* footer styling */
footer {
    background-color: #c28e78;
    color: #fff;
    text-align: center;
}

.footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
}

.footer-icons {
    display: flex;
    gap: 1rem;
}

.footer-icons img {
    width: 50px;
    height: 50px;
    object-fit: contain;
}

.footer-links {
    display: flex;
    gap: 1.5rem;
    font-size: 14px;
}

.footer-socials {
    margin-top: 1rem;
    display: flex;
    gap: 1rem;
    justify-content: center;
}

.footer-socials a {
    color: #fff;
    font-size: 18px;
    text-decoration: none;
}

.footer-socials a:hover {
    color: #ddd;
}

/* Products styling */
.products-container {
    text-align: left;
    padding: 2rem;
}

.products-container h2 {
    margin-bottom: 1rem;
    font-size: 24px;
    color: #333;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 0.5rem;
}

/* reduced gap */
product {
    width: 200px;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 1rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
    background-color: #fff;
}
