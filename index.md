
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">
    <link href="http://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css">

    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>EightySix Ops</title>
</head>

<body>
    <div id="container">
        <h1> RTH Inventory Tracker </h1>

        <div id="inputs-list" class="grid1">


            <div>
                <form action="" id="myForm">
                    <input id="input1" placeholder="Item " type="text" required> </div>

            <div>
                <input id="input2" placeholder="Quantity" type="text" required> </div>

            <div>
                <input id="input3" placeholder="Date" type="date" value="" required>
                </form>
            </div>


            <div>
                <button id='submit' class="fa-list-alt"> Add </button>
            </div>


        </div>

<!-- heading for div table  -->
        <div id='gridH'>
            <div>Item</div>
            <div>Quantity</div>
            <div>Purch Date</div>
            <div>ID</div>
            <div>Date</div>
            <div>Options</div>

        </div>
<!-- contents in the div table -->
        <div id='grid'>





        </div>


    </div>

    <script defer src="https://use.fontawesome.com/releases/v5.0.6/js/all.js"></script>

    <script src="EightySixOpsJS.js"></script>
</body>

</html>
