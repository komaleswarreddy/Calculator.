<!DOCTYPE html>
<html>
<head>
    <title>Simple Calculator</title>
</head>
<body>
    <h2>Simple Calculator</h2>
    <form method="get">
        <label for="expression">Enter your expression:</label>
        <input type="text" id="expression" name="expression" required>
        <button type="submit">Calculate</button>
    </form>

    <?php
    if(isset($_GET['expression'])) {
        $expression = $_GET['expression'];
        // Validate input to ensure it contains only valid mathematical characters and operators
        if(preg_match('/^[0-9+\-\/\*(). ]+$/', $expression)) {
            // Use eval() to evaluate the expression and obtain the result
            try {
                $result = eval("return $expression;");
                if($result !== FALSE) {
                    echo "<p>Result: $result</p>";
                } else {
                    echo "<p>Error: Invalid expression</p>";
                }
            } catch(Exception $e) {
                echo "<p>Error: " . $e->getMessage() . "</p>";
            }
        } else {
            echo "<p>Error: Invalid characters in expression</p>";
        }
    }
    ?>
</body>
</html>
