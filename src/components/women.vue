<template>
  <div class="women">
    
  </div>
</template>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script>
export default {
  name: 'women'
}

const URI = 'https://api.gilt.com/v1/sales/women/active.json?';
const APIkey = 'apikey=b089b1162895b96b190a895b6c849054704453656c2be416cb63f0cc58ac475f';

  fetch(URI + APIkey)
    .then(function(response) {
      return response.json();
    })
    .then(function(data) {
       let sales = data.sales;
      console.log(sales)
    })
    .catch(function(error) {
    });

//  $.ajax({
//       url: URI + API,
//       success: getInfo
//     });
</script>