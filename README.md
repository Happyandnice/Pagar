# Pagar
<?php
// SDK de Mercado Pago
require __DIR__ .  '/vendor/autoload.php';
?>
// Agrega credenciales
MercadoPago\SDK::setAccessToken('PROD_ACCESS_TOKEN');
?>
// Crea un objeto de preferencia
 $preference = new MercadoPago\Preference();

// Crea un ítem en la preferencia
$item = new MercadoPago\Item();
$item->title = 'Mi producto';
$item->quantity = 1;
$item->unit_price = 75.56;
$preference->items = array($item);
$preference->save();
?>
<script
https://happyandnice.com.mx/55276634306/checkouts/49f6b50c85b0de680bf2f574d2d7545f?skip_shopify_pay=true&locale=es
</script>
