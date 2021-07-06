

<style>
.item {
  border-bottom: 1px dashed #ccc;
  padding: 10px;
}
.item::after {
  content: "";
  display: block;
  clear: both;
}
.item-l {
  float: left;
  font-size: 0;
}
.item-r {
  float: left;
  padding-left: 20px;
}
.item-img {
  width: 100px;
  height: 100px;
  border: 1px solid #ccc;
}
.item-title {
  font-size: 14px;
  margin-top: 10px;
}
.item-title > small {
  color: #888;
  font-size: 12px;
}
.item-price {
  margin-top: 10px;
  color: #f00;
  font-size: 15px;
}
.item-opt {
  margin-top: 10px;
}
.item-opt button {
  border: 0;
  background: coral;
  color: #fff;
  padding: 4px 5px;
}
.item-total {
  margin: 10px;
  font-size: 15px;
}
.item-empty {
  text-align: center;
  margin-top: 20px;
  font-size: 15px;
}
</style>
