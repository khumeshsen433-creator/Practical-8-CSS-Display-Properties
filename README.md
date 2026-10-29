# Practical-8-CSS-Display-Properties
<!DOCTYPE html>
<html>
<head>
    <title>Display Properties</title>

    <style>
        .block {
            display: block;
            background: lightblue;
            margin: 5px;
            padding: 10px;
        }

        .inline {
            display: inline;
            background: yellow;
        }

        .inlineblock {
            display: inline-block;
            width: 120px;
            padding: 15px;
            margin: 5px;
            background: lightgreen;
        }

        .hide {
            display: none;
        }
    </style>
</head>
<body>

    <h1>CSS Display Demo</h1>

    <h2>Block</h2>
    <div class="block">Block 1</div>
    <div class="block">Block 2</div>

    <h2>Inline</h2>
    <span class="inline">Inline 1</span>
    <span class="inline">Inline 2</span>

    <h2>Inline-block</h2>
    <div class="inlineblock">Box 1</div>
    <div class="inlineblock">Box 2</div>

    <p class="hide">This text is hidden.</p>

</body>
</html>