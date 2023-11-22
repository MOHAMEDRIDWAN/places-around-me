# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Fork the repository to your github and clone it into a folder in github
### Step 2:
Then make sure that django is activated and then start a new django project
### Step 3:
Now create a folder called static and within that folder create a folder called html
### Step 4:
Now create a file called map.html in that folder
### Step 5:
Now open google maps and take a screenshot of your hometown
### Step 6:
Now open "imagemap.org" and upload your image there and generate image maps of that using the rectangular or circle tool
### Step 7:
Now inside the html folder create the necessary html files that you've included in the href of the image maps
### Step 8:
Now push the folder and commit the changes in the github
## Code:
### Map.html Code : 
```
<!DOCTYPE html>
<html>
<head>
    <title>imagemaps demo</title>
    <style>

        .body{
            background-image: url(main_bg.jpg);
        }
    </style>
</head>
<body class="body">
    <h1 style="color: crimson;font-size: 60px;" align="Center">Image Maps Demo</h1>
    <img src="Map.jpg" usemap="#image_map">
    <map name="image_map">
    <area alt="Avai Nadunillai School" title="Avai Nadunillai School" href="Avai.html" coords="571,266,829,397" shape="rect">
    <area alt="Asma Nursery and Primary School" title="Asma Nursery and Primary School" href="Asma.html" coords="1031,355,1242,492" shape="rect">
    <area alt="Rekha Medicals" title="Rekha Medicals" href="Rekha.html" coords="875,256,1055,371" shape="rect">
    <area alt="Herbalife Nutrition Center" title="Herbalife Nutrition Center" href="Nutrition.html" coords="1357,254,1617,389" shape="rect">
    <area alt="Candy Kids Play School" title="Candy Kids Play School" href="Candy.html" coords="799,6,1065,103" shape="rect">

    </map>
</body>
</html>
```

### Rekha.html code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rekha Medicals</title>
    <style>
        .Rekhaa{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
            height: 400px;
            width: 800px;
        }
        .para{
            width: 1700px;
            border: 15px solid brown;
            padding: 50px;
            margin: 20px;
            line-height: 75px;
        }
        .body{
            background-image: url(paper.jpg);
        }
     
    </style>
</head>
<body class="body">
    <h1 align="Center" style="font-size: 80px;font: bolder;">REKHA MEDICALS</h1>
    <br>
    <img src="Rekha_medicals.jpg" class="Rekhaa">
    <p align="just" style="font-size: 40px;font-family: sans-serif;" class="para">This is one of the famous Medical shop in our area.
        We can get access to all kind of medical supplies that
        we need here. It's one of the oldest medical shop in 
        our area too.Rekha Medicals, nestled in the heart of our 
        community, stands as a reliable beacon of health and 
        well-being. This pharmacy has become an indispensable
        part of our neighborhood, catering to the diverse medical
        needs of residents with unwavering dedication. 
        With its well-stocked shelves and a knowledgeable staff,
         Rekha Medicals ensures that customers have access to a 
         wide range of pharmaceuticals, over-the-counter 
         medications, and healthcare essentials. 
         The friendly and attentive team at Rekha Medicals
          goes beyond just dispensing prescriptions;
           they offer valuable advice and guidance, 
           fostering a sense of trust among patrons.
            Whether seeking medicines, medical supplies, 
            or a friendly face willing to provide assistance,
             Rekha Medicals is a trusted ally in our pursuit
              of good health.

    </p>
    
</body>
</html>
```

### Asma.html Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asma Nursery and Primary School</title>
    <style>
        .asma{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
            height: 400px;
            width: 800px;
        }
        .para{
            width: 1700px;
            border: 15px solid brown;
            padding: 50px;
            margin: 20px;
            line-height: 75px;
        }
        .body{
            background-image: url(paper.jpg);
        }
     
    </style>
</head>
<body class="body">
    <h1 align="Center" style="font-size: 80px;font: bolder;">ASMA NURSERY AND PRIMARY SCHOOL</h1>
    <br>
    <img src="Asma_school.jpg" class="asma">
    <p align="just" style="font-size: 40px;font-family: sans-serif;" class="para">
        Asma Nursery and Primary School stands as a beacon of educational excellence, fostering the growth of young minds with a commitment to holistic development. Nestled in a serene and conducive learning environment, the school prides itself on providing a nurturing space where children embark on their educational journey with enthusiasm and curiosity.

        At Asma Nursery and Primary School, we recognize the significance of early childhood education in laying the foundation for a child's future success. Our dedicated team of experienced educators strives to create a dynamic and engaging curriculum that blends academic rigor with creative exploration. The school's ethos is centered on cultivating not only intellectual abilities but also instilling values of empathy, resilience, and a love for learning.
        
        The classrooms at Asma Nursery and Primary School are vibrant spaces equipped with modern educational resources, fostering an interactive and stimulating learning experience. We believe in a well-rounded education that includes a mix of academics, arts, sports, and character-building activities, ensuring that students develop into confident and well-rounded individuals.
        
        Safety and well-being are paramount at Asma Nursery and Primary School. We maintain a secure and child-friendly environment, complete with age-appropriate facilities and a team of caring staff who prioritize the safety and happiness of every student.
        
        Furthermore, we understand the importance of collaboration between teachers and parents. Regular parent-teacher interactions, informative workshops, and open communication channels ensure that families are actively involved in their child's educational journey.
        
        In summary, Asma Nursery and Primary School is not just an educational institution; it is a community dedicated to nurturing the potential within each child. With a focus on academic excellence, character development, and a supportive learning environment, we aim to empower students to become lifelong learners and responsible global citizens.

    </p>
    
</body>
</html>
```

### Avai.html Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Avai Nadunillai School</title>
    <style>
        .img{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
            
        }
        .body{
            background-image: url(avai_back.jpg);
            background-repeat: no-repeat;
            background-attachment: fixed;
            
        }
        .para{
            width: 1700px;
            border: 15px solid red;
            padding: 50px;
            margin: 20px;
            line-height: 75px;
        }
    </style>
</head>
<body class="body">
    <h1 style="font-size: 70px;" align="Center">AVAI NADUNILLAI SCHOOL</h1>
    <img src="avai.png" class="img">
    <p align="just" style="font-size: 40px;font-family: sans-serif;" class="para">
        Avai Nadunillai School stands as a venerable institution in our community, proudly holding the distinction of being one of the oldest schools in the area. Established with a commitment to education, this institution has played a pivotal role in shaping the academic landscape of our locality. The rich history of Avai Nadunillai School is woven into the fabric of many families, including mine, as both my parents are proud alumni who fondly reminisce about their formative years spent within its walls.

The school's enduring legacy is a testament to its dedication to providing quality education, fostering a sense of community, and instilling values that extend beyond the classroom. With classes spanning up to the 8th grade, Avai Nadunillai School has been a constant presence in the lives of generations, offering a solid foundation for students as they progress through their academic journey.

As a symbol of continuity and tradition, the school holds a special place in the hearts of locals, serving as a hub for both education and nostalgia. The classrooms echo with the laughter and learning of students, creating an environment that encapsulates the essence of a time-honored educational institution. Avai Nadunillai School stands not just as a building but as a living testament to the enduring power of education and community in our lives.
    </p>
    
</body>
</html>
```

### Candy.html Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Candy Kids Play School</title>
    <style>
        .candy{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
            height: 400px;
            width: 800px;
        }
        .para{
            width: 1300px;
            border: 15px solid brown;
            padding: 50px;
            margin: 20px;
            line-height: 75px;
        }
        .body{
            background-image: url(paper.jpg);
        }
     
    </style>
</head>
<body class="body">
    <h1 align="Center" style="font-size: 80px;font: bolder;">CANDY KIDS PLAY SCHOOL</h1>
    <br>
    <img src="candy.png" class="candy">
    <p align="just" style="font-size: 40px;font-family: sans-serif;" class="para">
        Candy Kids Play School is a vibrant and nurturing educational environment dedicated to fostering the growth and development of young minds. Nestled in a cheerful and colorful setting, the school is designed to create a joyful and stimulating atmosphere that sparks the curiosity and creativity of every child who walks through its doors.

        At Candy Kids Play School, we believe in providing a solid foundation for a child's future through a combination of play-based learning and structured educational activities. Our experienced and passionate team of educators is committed to ensuring that each child receives personalized attention, guiding them through the exciting journey of early childhood education.

        The curriculum at Candy Kids Play School is thoughtfully crafted to incorporate a variety of activities that cater to the holistic development of children. From engaging storytelling sessions to hands-on arts and crafts, we strive to make learning a fun and interactive experience. Our play-based approach is designed to not only build academic skills but also instill important social and emotional values.

        Safety is our top priority at Candy Kids Play School. We maintain a secure and nurturing environment, complete with age-appropriate facilities and equipment. Our classrooms are equipped with educational toys and materials that encourage exploration and discovery, fostering a love for learning from an early age.
    </p>
    
</body>
</html>
```

### Nutrition.html Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Herballife Nutrition center</title>
    <style>
        .Rekhaa{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
            height: 400px;
            width: 800px;
        }
        .para{
            width: 1700px;
            border: 15px solid green;
            padding: 50px;
            margin: 20px;
            line-height: 75px;
        }
        .body{
            background-image: url(paper.jpg);
        }
     
    </style>
</head>
<body class="body">
    <h1 align="Center" style="font-size: 80px;font: bolder;">Herballife Nutrition Center</h1>
    <br>
    <img src="herbal.png" class="Rekhaa">
    <p align="just" style="font-size: 40px;font-family: sans-serif;" class="para">
        Herbalife Nutrition Center, located in west tambaram, is a dedicated hub for health and wellness that offers a wide range of Herbalife nutritional products and services. As a global nutrition company, Herbalife is committed to helping people achieve their health and fitness goals through personalized nutrition plans and high-quality supplements.

        At the Herbalife Nutrition Center in west tambaram, you can find a knowledgeable and friendly team of wellness coaches who are ready to assist you on your journey to better health. These coaches are trained to provide personalized advice and guidance based on your individual needs and goals. Whether you're looking to lose weight, gain muscle, or simply improve your overall well-being, the Herbalife Nutrition Center is equipped to support you.

        The center provides a variety of Herbalife products, including meal replacement shakes, nutritional supplements, and snacks that are designed to support a balanced and healthy lifestyle. These products are backed by scientific research and are known for their quality and effectiveness.

        In addition to product offerings, the Herbalife Nutrition Center in west tambaram may host events, workshops, and challenges to foster a sense of community and encourage individuals to stay committed to their health and fitness goals. These events provide an opportunity for like-minded individuals to connect, share experiences, and learn more about leading a healthy lifestyle.

        Whether you are a long-time Herbalife enthusiast or someone exploring the brand for the first time, the Herbalife Nutrition Center in west tambaram serves as a valuable resource for those seeking personalized nutrition solutions and a supportive community to help them on their wellness journey.
    </p>
    
</body>
</html>
```

## Output:
### Map.html output:
![map_out](https://github.com/arbasil05/places-around-me/assets/144218037/58f7e5f4-a77b-4ae6-9add-0fb2a3bfa04e)
### Rekha.html output:
![rekha_out](https://github.com/arbasil05/places-around-me/assets/144218037/f27206aa-d45c-4852-a7d9-f0e34a98eac9)
### Candy.html output:
![candy_out](https://github.com/arbasil05/places-around-me/assets/144218037/33074cd5-c0aa-4ca1-879d-0aad96a577fb)
### Herbal.html output:
![herbal_out](https://github.com/arbasil05/places-around-me/assets/144218037/cc02d9b7-d442-4bdc-bf31-f67ca766a2c8)
### avai.html output:
![avai_out](https://github.com/arbasil05/places-around-me/assets/144218037/7a17b9b6-8c96-4daa-a46e-8b811b488197)
### asma.html output:
![asma_out](https://github.com/arbasil05/places-around-me/assets/144218037/887354a7-07b8-4d5f-a7bc-739def9bd454)

## Result:
Image maps have been sucessfully developed

