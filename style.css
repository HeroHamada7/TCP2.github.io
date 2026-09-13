const productImage =
    document.getElementById("productImage");

const productVisual =
    document.querySelector(".product-visual");


/* =========================================
   IMAGE PARALLAX
========================================= */

productVisual.addEventListener("mousemove", (event) => {

    const rect =
        productVisual.getBoundingClientRect();

    const x =
        (event.clientX - rect.left) / rect.width;

    const y =
        (event.clientY - rect.top) / rect.height;


    const moveX =
        (x - 0.5) * 10;

    const moveY =
        (y - 0.5) * 10;


    productImage.style.transform =
        `scale(1.06) translate(${moveX}px, ${moveY}px)`;

});


productVisual.addEventListener("mouseleave", () => {

    productImage.style.transform =
        "scale(1) translate(0,0)";

});



/* =========================================
   PAGE LOAD ANIMATION
========================================= */

document.addEventListener("DOMContentLoaded", () => {

    document.body.classList.add("loaded");

});
