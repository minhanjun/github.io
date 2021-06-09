<html>
    <script>
        const filters = [
          {vendorId: 0x1209, productId: 0xa800},
        ];

        navigator.usb.requestDevice({filters: filters});

    </script>
</html>