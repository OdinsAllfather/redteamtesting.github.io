<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mosquito Information Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #e6f0e2; /* Light green background */
            color: #2c3e2d; /* Dark green text */
        }
        h1, h2, h3 {
            color: #1a4a1c; /* Deeper green for headers */
        }
        .dropdown {
            margin-bottom: 20px;
            background-color: #c1d9bf; /* Soft green for dropdown sections */
            padding: 10px;
            border-radius: 5px;
        }
        .fill-in-blank {
            margin-top: 30px;
            background-color: #d3e4d1; /* Another soft green for fill-in-blank sections */
            padding: 10px;
            border-radius: 5px;
        }
        input[type="text"] {
            width: 200px;
            padding: 5px;
            border: 1px solid #5b8c5a; /* Green border for input fields */
            background-color: #f0f7ee; /* Very light green background for input fields */
        }
        select {
            padding: 5px;
            border: 1px solid #5b8c5a; /* Green border for dropdowns */
            background-color: #f0f7ee; /* Very light green background for dropdowns */
        }
        p {
            background-color: rgba(255, 255, 255, 0.5); /* Semi-transparent white background for better readability */
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Mosquito Information Hub</h1>

    <h2>About Mosquitoes</h2>
    <p>Mosquitoes are small, flying insects known for their ability to bite humans and animals. They belong to the family Culicidae and are found in almost every part of the world. There are over 3,500 species of mosquitoes, but only a few hundred are known to bite humans.</p>

    <h2>Mosquito Life Cycle</h2>
    <p>Mosquitoes go through four stages in their life cycle: egg, larva, pupa, and adult. The first three stages are aquatic, while the adult stage is terrestrial. Female mosquitoes lay their eggs in standing water, which can include natural bodies of water or artificial containers.</p>

    <h2>Mosquito-borne Diseases</h2>
    <p>Mosquitoes are vectors for various diseases, including malaria, dengue fever, Zika virus, West Nile virus, and yellow fever. These diseases affect millions of people worldwide each year, making mosquito control a crucial public health concern.</p>

    <h2>Test Your Mosquito Knowledge</h2>
    <div class="dropdown">
        <p>How many species of mosquitoes are there?</p>
        <select>
            <option>Select an answer</option>
            <option>Around 100</option>
            <option>About 1,000</option>
            <option>Over 3,500</option>
            <option>More than 10,000</option>
        </select>
    </div>

    <div class="dropdown">
        <p>Which stage of a mosquito's life cycle is not aquatic?</p>
        <select>
            <option>Select an answer</option>
            <option>Egg</option>
            <option>Larva</option>
            <option>Pupa</option>
            <option>Adult</option>
        </select>
    </div>

    <div class="dropdown">
        <p>Which of the following is not a mosquito-borne disease?</p>
        <select>
            <option>Select an answer</option>
            <option>Malaria</option>
            <option>Dengue fever</option>
            <option>Influenza</option>
            <option>West Nile virus</option>
        </select>
    </div>

    <div class="dropdown">
        <p>What do female mosquitoes need to produce eggs?</p>
        <select>
            <option>Select an answer</option>
            <option>Sugar water</option>
            <option>Blood meal</option>
            <option>Plant nectar</option>
            <option>Fruit juice</option>
        </select>
    </div>

    <h2>Fill in the Blanks</h2>
    <div class="fill-in-blank">
        <h3><!-- TITLE 1 PLACEHOLDER --></h3>
        <p>Mosquitoes are attracted to <input type="text" placeholder="Answer 1"> and <input type="text" placeholder="Answer 2"> produced by humans and animals.</p>
    </div>

    <div class="fill-in-blank">
        <h3><!-- TITLE 2 PLACEHOLDER --></h3>
        <p>The most effective way to control mosquito populations is to eliminate <input type="text" placeholder="Answer 3"> where they lay their eggs.</p>
    </div>

    <div class="fill-in-blank">
        <h3><!-- TITLE 3 PLACEHOLDER --></h3>
        <p>Mosquitoes can detect human presence from up to <input type="text" placeholder="Answer 4"> feet away, primarily through sensing <input type="text" placeholder="Answer 5"> and body heat.</p>
    </div>
</body>
</html>
