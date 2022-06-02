<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Assignment Solution for Module 2</title>
    <style>
        /********** Base styles **********/
        
        * {
            box-sizing: border-box;
        }
        
        h1 {
            padding: 50px;
            text-align: center;
            margin-bottom: 50px;
        }
        /* Simple Responsive Framework. */
        
        .row {
            width: 100%;
            text-align: right;
            background-color: rgb(255, 255, 255);
        }
        
        .top {
            height: 30px;
            border: 2px solid black;
            margin-left: 293px;
            background-color: rgba(216, 112, 147, 0.922);
        }
        
        .top2 {
            height: 60px;
            border: 2px solid black;
            margin-left: 293px;
            background-color: rgba(220, 20, 60, 0.846);
        }
        
        .top3 {
            height: 30px;
            border: 2px solid black;
            margin-left: 293px;
            background-color: rgba(255, 255, 0, 0.76);
        }
        
        .col-lg-1,
        .col-lg-2,
        .col-lg-3 {
            border: solid;
            text-align: right;
            background-color: grey;
        }
        
        .col-md-1,
        .col-md-2,
        .col-md-3 {
            border: solid;
            text-align: right;
            background-color: grey;
        }
        
        .inner {
            text-align: left;
            padding-left: 3%;
            margin: 4%;
            padding-top: 5%;
        }
        /********** Large devices only **********/
        
        @media (min-width: 992px) {
            .col-lg-1,
            .col-lg-2,
            .col-lg-3 {
                float: left;
            }
            .col-lg-1 {
                width: 12.33%;
            }
            .col-lg-2 {
                width: 22.66%;
            }
            .col-lg-3 {
                width: 32%;
            }
        }
        /********** Medium devices only **********/
        
        @media (min-width: 768px) and (max-width: 991px) {
            .col-md-1,
            .col-md-2,
            .col-md-3 {
                float: left;
                border: 1px solid green;
            }
            .col-md-1 {
                width: 10.33%;
            }
            .col-md-2 {
                width: 20.66%;
            }
            .col-md-3 {
                width: 30%;
            }
        }
        /********** small devices only **********/
        
        @media (max-width: 767px) {
            .col-md-1,
            .col-md-2,
            .col-md-3 {
                float: left;
                border: 1px solid green;
            }
            .col-md-1 {
                width: 10.33%;
            }
            .col-md-2 {
                width: 20.66%;
            }
            .col-md-3 {
                width: 30%;
            }
        }
    </style>
</head>

<body>
    <h1 class="box"><u><b>OUR MENU</b></u></h1>

    <div class="row">
        <div class="col-lg-3 col-md-6">
            <span class="top">CHICHEN</span>
            <div class="inner">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam dignissimos iusto nemo, itaque ad quaerat sunt minus ipsam nesciunt vel tenetur ab consequuntur ullam voluptates exercitationem repellendus laudantium. Sapiente, repudiandae.</div>
        </div>
        <div class="col-lg-3 col-md-6">
            <span class="top2">BEEF</span>
            <div class="inner">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam dignissimos iusto nemo, itaque ad quaerat sunt minus ipsam nesciunt vel tenetur ab consequuntur ullam voluptates exercitationem repellendus laudantium. Sapiente, repudiandae.</div>
        </div>
        <div class="col-lg-3 col-md-6">
            <span class="top3">SUSHI</span>
            <div class="inner">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam dignissimos iusto nemo, itaque ad quaerat sunt minus ipsam nesciunt vel tenetur ab consequuntur ullam voluptates exercitationem repellendus laudantium. Sapiente, repudiandae.</div>
        </div>

    </div>

</body>

</html>
