Introduction
============

This is guide for Dinions devices, or simply "dinions".

Architecture
============

Each device has an API.
Below is Minimal API in each device available


Device Info
++++++++++++

.. http:get::  /device/info

    Returns the basic information about the device including its product type and model number.

    **Example request**:

    .. prompt:: bash $

        curl https://<device-ip>/device/info

    **Example response**:

    .. sourcecode:: js

        {
            "product_family": "displays",
            "product_type": "lcd_displays",
            "product_name": "Dinion LCD 16x2"
        }

List Webhooks
+++++++++++++

.. http:get::  /webhook/index

    TBD - Returns the basic information about the device including its product type and model number.

    **Example request**:

    .. prompt:: bash $

        curl https://<device-ip>/device/info

    **Example response**:

    .. sourcecode:: js

        {
            "product_family": "displays",
            "product_type": "lcd_displays",
            "product_name": "Dinion LCD 16x2"
        }


Set Webhook
+++++++++++

.. http:post::  /webhook/set/<webhook-key>

    TBD - Returns the basic information about the device including its product type and model number.

    **Example request**:

    .. prompt:: bash $

        curl https://<device-ip>/device/info

    **Example response**:

    .. sourcecode:: js

        {
            "product_family": "displays",
            "product_type": "lcd_displays",
            "product_name": "Dinion LCD 16x2"
        }



