//Calculate New JV Price
_DiscountedPrice = LAMBDA(price, discount,  //add the name
    round(price*(1-discount),2)
);
