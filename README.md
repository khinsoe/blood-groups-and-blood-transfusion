<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blood Groups and Blood Transfusion</title>
    <style>
        /* CSS for the Presentation Layout and Basic Slide Transitions */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            overflow: hidden; /* Hide scrollbars */
            display: flex;
            flex-direction: column;
            height: 100vh;
            background-color: #f4f4f4;
        }

        #presentation-container {
            flex-grow: 1;
            position: relative;
            overflow: hidden;
        }

        .slide {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: none; /* Hidden by default */
            padding: 40px;
            box-sizing: border-box;
            background-color: white;
            transition: opacity 0.5s ease-in-out; /* Fade transition */
            opacity: 0;
            display: grid;
            grid-template-columns: 1fr 1fr; /* Two columns for content and diagram */
            gap: 20px;
        }

        .slide.active {
            display: grid;
            opacity: 1;
        }

        .controls {
            padding: 10px;
            text-align: center;
            background-color: #333;
        }

        .controls button {
            padding: 10px 20px;
            margin: 0 10px;
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
        }

        .content-area {
            text-align: left;
        }

        .media-area {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .media-area img {
            max-width: 100%;
            max-height: 100%;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>

    <div id="presentation-container">
        <div class="slide active" data-narration="Welcome to this presentation on the blood groups and blood transfusion. This knowledge is essential for every dental and medical professional, especially when dealing with surgical procedures, trauma care, and emergency medicine. This presentation was created by Dr Khin Soe.">
            <div class="content-area">
                <h2>❤ Blood Groups and Blood Transfusion</h2>
                <p>Welcome to this presentation on the blood groups and blood transfusion. This knowledge is essential for every dental and medical professional, especially when dealing with surgical procedures, trauma care, and emergency medicine.</p>
                <p>This presenation was created by Dr Khin Soe.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media2.giphy.com/media/3NgjRZvcpbnnAaZwNI/giphy.gif" alt="Surgical team">
            </div>
        </div>
		
		<div class="slide" data-narration="Agglutinogens refer to the antigens present on the cell membranes of red blood cells (RBCs). Agglutinins refer to the antibodies against the agglutinogens. These are present in the plasma.">
            <div class="content-area">
                <h2>❤ Agglutinogens and agglutinins</h2>
                <p>Agglutinogens refer to the antigens present on the cell membranes of red blood cells (RBCs).</p>
                <p>Agglutinins refer to the antibodies against the agglutinogens. These are present in the plasma.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i0.wp.com/biomedguide.com/wp-content/uploads/2020/07/rbc_w-antigens.png?fit=822%2C439&ssl=1" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Agglutination of RBCs can be caused by the antigens present on their cell membranes in the presence of suitable agglutinins (antibodies). That is why these antigens are called agglutinogens.">
            <div class="content-area">
                <h2>Agglutination of RBCs</h2>
                <p>Agglutination of RBCs can be caused by the antigens present on their cell membranes in the presence of suitable agglutinins (antibodies).</p>
                <p>That is why these antigens are called agglutinogens.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i.makeagif.com/media/5-24-2022/eORp44.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Karl Landsteiner in 1900 framed a law in relation to agglutinogens and agglutinins, which states that: 1. If an agglutinogen is present on the red cell membrane of an individual, the corresponding agglutinin must be absent in the plasma.">
            <div class="content-area">
                <h2>Landsteiner law</h2>
                <p>Karl Landsteiner in 1900 framed a law in relation to agglutinogens and agglutinins, which states that:</p>
                <p>1. If an agglutinogen is present on the red cell membrane of an individual, the corresponding agglutinin must be absent in the plasma.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="image-1.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="2. If an agglutinogen is absent from the cell membrane of RBCs of an individual, the corresponding agglutinin must be present in the plasma.">
            <div class="content-area">
                <h2>Landsteiner law</h2>
                <p>2. If an agglutinogen is absent from the cell membrane of RBCs of an individual, the corresponding agglutinin must be present in the plasma.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="image-2.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The classical ABO blood grouping system is based on the presence of A and B agglutinogens on the cell membrane of RBCs.">
            <div class="content-area">
                <h2>CLASSICAL ABO BLOOD GROUPING SYSTEM</h2>
                <p>The classical ABO blood grouping system is based on the presence of A and B agglutinogens on the cell membrane of RBCs.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i.ytimg.com/vi/5vywZHf_scA/maxresdefault.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="A and B agglutinogens are complex oligosaccharides differing in their terminal sugars.">
            <div class="content-area">
                <h2>A AND B AGGLUTINOGENS</h2>
                <p>A and B agglutinogens are complex oligosaccharides differing in their terminal sugars.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media.giphy.com/media/oLIZyWASoBuAU/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Anti-A (or α) agglutinin and anti-B (or β) agglutinin refer to the antibody, i.e. which reacts with or acts on the antigen A and antigen B, respectively.">
            <div class="content-area">
                <h2>ANTI-A AND ANTI-B AGGLUTININS</h2>
                <p>Anti-A (or α) agglutinin and anti-B (or β) agglutinin refer to the antibody, i.e. which reacts with or acts on the antigen A and antigen B, respectively.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://study.com/cimages/videopreview/videopreview-full/7.71_109706.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="There are two types of α agglutinins: the α1 and α proper. The α and β agglutinins are globulins of IgM type and cannot cross the placenta.">
            <div class="content-area">
                <h2>ANTI-A AND ANTI-B AGGLUTININS</h2>
                <p>There are two types of α agglutinins: the α1 and α proper.</p>
                <p>The α and β agglutinins are globulins of IgM type and cannot cross the placenta.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media.istockphoto.com/id/1453953298/photo/the-gold-nanoparticle-biosensor-vessel.jpg?s=1024x1024&w=is&k=20&c=sdcpyuII5D6zQVe8rhj0pdu9CdRymKpA44Drt2zPfuo=" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The α and β agglutinins act best at low temperature (5–20°C) and are therefore also called as cold antibodies.">
            <div class="content-area">
                <h2>ANTI-A AND ANTI-B AGGLUTININS</h2>
                <p>The α and β agglutinins act best at low temperature (5–20°C) and are therefore also called as cold antibodies.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i.ytimg.com/vi/S0ig52vf4sk/maxresdefault.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Blood group A is characterized by Presence of A agglutinogen and absence of B agglutinogen on the cell membrane of RBCs and Presence of anti-B agglutinin and absence of anti-A agglutinin from the plasma.">
            <div class="content-area">
                <h2>Blood group A</h2>
                <p>Blood group A is characterized by:</p>
                <p>Presence of A agglutinogen and absence of B agglutinogen on the cell membrane of RBCs and</p>
				<p>Presence of anti-B agglutinin and absence of anti-A agglutinin from the plasma.</p>
            </div>
            <div class="media-area">
                <img src="https://thumbs.dreamstime.com/b/blood-group-testing-slide-agglutination-method-lab-grouping-275090897.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Blood group B is characterized by Presence of B agglutinogen and absence of A agglutinogen on the cell membrane of RBCs and Presence of anti-A agglutinin and absence of anti-B agglutinin from the plasma.">
            <div class="content-area">
                <h2>Blood group B</h2>
                <p>Blood group B is characterized by:</p>
                <p>Presence of B agglutinogen and absence of A agglutinogen on the cell membrane of RBCs and</p>
				<p>Presence of anti-A agglutinin and absence of anti-B agglutinin from the plasma.</p>
            </div>
            <div class="media-area">
                <img src="https://ak.picdn.net/shutterstock/videos/1012495730/thumb/3.jpg?ip=x480" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Blood group AB is characterized by Presence of both A and B agglutinogens on the cell membrane of RBCs, and Absence of both anti-A and anti-B agglutinins from the plasma">
            <div class="content-area">
                <h2>Blood group AB</h2>
                <p>Blood group AB is characterized by:</p>
                <p>Presence of both A and B agglutinogens on the cell membrane of RBCs, and</p>
				<p>Absence of both anti-A and anti-B agglutinins from the plasma.</p>
            </div>
            <div class="media-area">
                <img src="https://image.shutterstock.com/image-photo/abo-blood-grouping-by-slide-260nw-716420524.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Blood group O is characterized by Absence of both A and B agglutinogens on the red cell membrane and Presence of both anti-A and anti-B agglutinins in the plasma.">
            <div class="content-area">
                <h2>Blood group O</h2>
                <p>Blood group O is characterized by:</p>
                <p>Absence of both A and B agglutinogens on the red cell membrane and, </p>
				<p>Presence of both anti-A and anti-B agglutinins in the plasma.</p>
            </div>
            <div class="media-area">
                <img src="https://media.gettyimages.com/id/1175888775/photo/a-slide-of-human-blood-being-held-by-a-technican.jpg?s=612x612&w=gi&k=20&c=yOh4JWjU7S8TP4VISblaWFQhji8Jfy5ejXGcArKEKms=" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Agglutinogens A and B or the non-antigenic substances which determine the blood groups are genetically inherited as Mendelian dominant in the classical Mendelian pattern.">
            <div class="content-area">
                <h2>INHERITANCE OF ABO BLOOD GROUPS</h2>
                <p>Agglutinogens A and B or the non-antigenic substances which determine the blood groups are genetically inherited as Mendelian dominant in the classical Mendelian pattern.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="image-3.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="">
            <div class="content-area">
                <h2>DETERMINATION OF ABO BLOOD GROUPS</h2>
                <p></p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="image-6.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The ABO blood group of an individual can be determined by mixing one drop of suspension of the red cells (in isotonic saline) with a drop each of anti-serum A and anti-serum B separately on a glass slide.">
            <div class="content-area">
                <h2>DETERMINATION OF ABO BLOOD GROUPS</h2>
                <p>The ABO blood group of an individual can be determined by mixing one drop of suspension of the red cells (in isotonic saline) with a drop each of anti-serum A and anti-serum B separately on a glass slide.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="image-4.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The antigens responsible for Rh blood grouping system are called Rh antigens or Rh agglutinogens or Rh factor because these were first discovered in the RBCs of rhesus monkeys.">
            <div class="content-area">
                <h2>RHESUS (Rh) BLOOD GROUPING SYSTEM</h2>
                <p>The antigens responsible for Rh blood grouping system are called Rh antigens or Rh agglutinogens or Rh factor because these were first discovered in the RBCs of rhesus monkeys.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://microbenotes.com/wp-content/uploads/2018/05/Rh-Blood-Group-System.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Three types of Rh antigens, viz. C, D and E have been recognized. However, D antigen is commonest and produces worst transfusion reactions. Therefore, for all practical purposes the term Rh antigen refers to D antigen.">
            <div class="content-area">
                <h2></h2>
                <p>Three types of Rh antigens, viz. C, D and E have been recognized. However, D antigen is commonest and produces worst transfusion reactions.</p>
                <p>Therefore, for all practical purposes the term Rh antigen refers to D antigen.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://images.interestingengineering.com/2023/04/11/image/jpeg/aABrjN6MJzcZuo9eEC5p492g0YPvoxLfG9AlWpJj.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Rh antibodies (also called anti-D) are produced only when an Rh −ve individual is transfused with Rh +ve blood">
            <div class="content-area">
                <h2>Rh ANTIBODIES</h2>
                <p>Rh antibodies (also called anti-D) are produced only when an Rh −ve individual is transfused with Rh +ve blood</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://www.medgif.com/wp-content/uploads/2017/01/1ea593c47de08aec92dfd94589d0a25c.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="When a Rh −ve mother gives birth to Rh +ve baby (Rh +ve RBCs of fetus enter into the maternal circulation), Rh antibodies are of IgG type and can cross the placenta.">
            <div class="content-area">
                <h2></h2>
                <p>When a Rh −ve mother gives birth to Rh +ve baby (Rh +ve RBCs of fetus enter into the maternal circulation), Rh antibodies are of IgG type and can cross the placenta.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media4.giphy.com/media/9LWaBStw4niBuQy4UZ/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Since these react best at body temperature so are also called warm antibodies. Once produced, the Rh antibodies persist in the blood for years and can produce serious reactions during the second transfusion.">
            <div class="content-area">
                <h2></h2>
                <p>Since these react best at body temperature so are also called warm antibodies.</p>
                <p>Once produced, the Rh antibodies persist in the blood for years and can produce serious reactions during the second transfusion.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media.giphy.com/media/3oEdvdGa32GG9gnuN2/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="When a Rh −ve mother (genotypes dd) bears a Rh +ve child (genotype Dd) with father being Rh +ve (genotype DD or Dd) at the time of delivery, the fetal RBCs enter maternal circulation because of severance of umbilical cord.">
            <div class="content-area">
                <h2>Mechanism of haemolytic disease of newborn in Rh incompatibility</h2>
				<h3>1. Entrance of Rh +ve fetal RBCs into Rh −ve mother’s circulation during first pregnancy.</h3>
                <p>When a Rh −ve mother (genotypes dd) bears a Rh +ve child (genotype Dd) with father being Rh +ve (genotype DD or Dd) at the time of delivery, the fetal RBCs enter maternal circulation because of severance of umbilical cord.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media1.tenor.com/m/twXZ9pOhcu4AAAAC/baby-give-birth.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Before delivery, usually the fetal and maternal circulation do not mix. Since the Rh +ve RBCs enter maternal circulation during delivery, so the first child is usually normal.">
            <div class="content-area">
                <h2>Mechanism of haemolytic disease of newborn in Rh incompatibility</h2>
				<h3>1. Entrance of Rh +ve fetal RBCs into Rh −ve mother’s circulation during first pregnancy.</h3>
                <p>Before delivery, usually the fetal and maternal circulation do not mix. Since the Rh +ve RBCs enter maternal circulation during delivery, so the first child is usually normal.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://64.media.tumblr.com/07563c11a70cdf96686c1af71865f4ca/tumblr_inline_pkojan1EjA1sgchcb_500.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="During postpartum period, i.e. within a month after delivery, the mother develops Rh antibodies in her blood.">
            <div class="content-area">
                <h2>Mechanism of haemolytic disease of newborn in Rh incompatibility</h2>
				<h3>2. Production of Rh antibodies (anti-D) in mother.</h3>
                <p>During postpartum period, i.e. within a month after delivery, the mother develops Rh antibodies in her blood.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media.giphy.com/media/l0ExlgRdiHMMtVXY4/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="When the Rh −ve mother in the second pregnancy also bears a Rh +ve child, the Rh antibodies present in the mother’s blood enter the fetal circulation by crossing the placental barrier and cause agglutination of fetal RBCs leading to haemolytic disease of newborn.">
            <div class="content-area">
                <h2>Mechanism of haemolytic disease of newborn in Rh incompatibility</h2>
				<h3>3. Rh incompatibility reaction during second pregnancy.</h3>
                <p>When the Rh −ve mother in the second pregnancy also bears a Rh +ve child, the Rh antibodies present in the mother’s blood enter the fetal circulation by crossing the placental barrier and cause agglutination of fetal RBCs leading to haemolytic disease of newborn.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://media.giphy.com/media/l0Exs3KvccCAQDqmY/giphy.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Depending upon the severity, the haemolytic disease of newborn may manifest as Erythroblastosis fetalis.">
            <div class="content-area">
                <h2>Manifestations of haemolytic disease of newborn</h2>
				<h3></h3>
                <p>Depending upon the severity, the haemolytic disease of newborn may manifest as Erythroblastosis fetalis.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i.ytimg.com/vi/zLE_l2ssDLU/maxresdefault.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Erythroblastosis fetalis is characterized by appearance of large number of erythroblasts in the peripheral blood occurs as the haemopoietic tissue of the baby attempts to rapidly replace the haemolysed RBCs.">
            <div class="content-area">
                <h2>1. Erythroblastosis fetalis.</h2>
				<h3>Erythroblastosis</h3>
                <p>Erythroblastosis fetalis is characterized by appearance of large number of erythroblasts in the peripheral blood occurs as the haemopoietic tissue of the baby attempts to rapidly replace the haemolysed RBCs.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://www.anthromania.com/wp-content/uploads/2023/06/Erythroblastosis-750x575.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Anaemia occurs due to excessive haemolysis of RBCs by Rh antibodies. Infant may even die of severe anaemia.">
            <div class="content-area">
                <h2>1. Erythroblastosis fetalis.</h2>
				<h3>Anaemia</h3>
                <p>Anaemia occurs due to excessive haemolysis of RBCs by Rh antibodies. Infant may even die of severe anaemia.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://assets.lybrate.com/f_auto,c_limit,w_3840,q_auto/eagle/uploads/cca97c80d89ae5468547088748abbee7/2f4f86.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="In Icterus gravis neonatorum Jaundice may occur within 24 h of birth due to excessive formation of bilirubin as a result of excessive haemolysis of RBCs. Liver and spleen are enlarged.">
            <div class="content-area">
                <h2>2. Icterus gravis neonatorum.</h2>
				<h3></h3>
                <p></p>
                <p>Jaundice may occur within 24 h of birth due to excessive formation of bilirubin as a result of excessive haemolysis of RBCs.</p>
				<p>Liver and spleen are enlarged.</p>
            </div>
            <div class="media-area">
                <img src="https://image.slidesharecdn.com/icterusneonatorumpurnima-210616162116/85/icterus-neonatorum-presentation-for-students-2-638.jpg?cb=1666114579" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Kernicterus is a neurological syndrome occurring in newborns with severe haemolysis. The excessive bilirubin formed may enter the brain tissue as the blood–brain barrier is not well developed in infants and cause damage.">
            <div class="content-area">
                <h2>3. Kernicterus</h2>
				<h3></h3>
                <p>Kernicterus is a neurological syndrome occurring in newborns with severe haemolysis.</p>
                <p>The excessive bilirubin formed may enter the brain tissue as the blood–brain barrier is not well developed in infants and cause damage.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://i.ytimg.com/vi/UTBs-Wdf3UU/maxresdefault.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Hydrops fetalis is a condition which the fetus is grossly oedematous. It occurs when haemolysis is very severe. Usually, there occurs intrauterine death of fetus or if born prematurely or even at term, the infant dies within a few hours.">
            <div class="content-area">
                <h2>4. Hydrops fetalis</h2>
				<h3></h3>
                <p>Hydrops fetalis is a condition which the fetus is grossly oedematous. It occurs when haemolysis is very severe.</p>
                <p>Usually, there occurs intrauterine death of fetus or if born prematurely or even at term, the infant dies within a few hours.</p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://tse1.explicit.bing.net/th/id/OIP.xrUCMh7deWeL8sV0XBaSBwHaFi?rs=1&pid=ImgDetMain&o=7&rm=3" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="The haemolytic disease in the newborn during second pregnancy can be prevented by injecting single dose of Rh antibodies (anti-D) in the form of Rh-immunoglobulin to mother soon after child birth.">
            <div class="content-area">
                <h2>Prevention of haemolytic disease of newborn</h2>
				<h3></h3>
                <p>The haemolytic disease in the newborn during second pregnancy can be prevented by injecting single dose of Rh antibodies (anti-D) in the form of Rh-immunoglobulin to mother soon after child birth.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://c8.alamy.com/comp/2PYWJAD/cairo-egypt-may-2-2023-human-anti-d-rh-immunoglobulin-rhophylac-300-g-micrograms-1500-iu-for-iv-or-im-injection-for-prevention-of-rhd-immuniza-2PYWJAD.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Treatment of haemolytic disease of the newborn is replacement of baby’s Rh +ve blood with Rh −ve blood exchange transfusion.">
            <div class="content-area">
                <h2>Treatment of haemolytic disease of newborn</h2>
				<h3></h3>
                <p>Treatment of haemolytic disease of the newborn is replacement of baby’s Rh +ve blood with Rh −ve blood exchange transfusion.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://image4.slideserve.com/8878608/exchange-transfusion-l.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="CLINICAL APPLICATIONS OF BLOOD GROUPING can be done in blood transfusion, in preventing haemolytic disease in newborn, in paternity disputes, in medicolegal cases, and in knowing susceptibility to diseases.">
            <div class="content-area">
                <h2>CLINICAL APPLICATIONS OF BLOOD GROUPING</h2>
				<h3></h3>
                <p>1. In blood transfusion.</p>
                <p>2. In preventing haemolytic disease in newborn.</p>
				<p>3. In paternity disputes.</p>
				<p>4. In medicolegal cases and</p>
				<p>5. In knowing susceptibility to diseases.</p>
            </div>
            <div class="media-area">
                <img src="image-5.jpg" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Common situations in which blood transfusion is indicated are Blood loss, for quick restoration of haemoglobin, exchange transfusion, blood diseases and acute poisoning.">
            <div class="content-area">
                <h2>BLOOD TRANSFUSION</h2>
				<h3>INDICATIONS</h3>
                <p>Common situations in which blood transfusion is indicated are Blood loss, for quick restoration of haemoglobin, exchange transfusion, blood diseases and acute poisoning.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://www.medgif.com/wp-content/uploads/2017/01/1ea593c47de08aec92dfd94589d0a25c.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Donor refers to a person who donates the blood and the person who receives blood is a recipient.">
            <div class="content-area">
                <h2>BLOOD TRANSFUSION</h2>
				<h3>DONOR AND RECIPIENT</h3>
                <p>Donor refers to a person who donates the blood and the person who receives blood is a recipient.</p>
                <p></p>
				<p></p>
            </div>
            <div class="media-area">
                <img src="https://www.nhlbi.nih.gov/sites/default/files/2023-06/Whole-Blood-Transfusion-Parts_Social-Media-Animated-GIF_0.gif" alt=" ">
            </div>
        </div>
		
		<div class="slide" data-narration="Autologous blood transfusion refers to transfusion of an individual’s own blood which has been withdrawn and stored. Autologous transfusion is done under the following situations: such as For elective surgery, During surgery, and Some sports persons.">
            <div class="content-area">
                <h2>BLOOD TRANSFUSION</h2>
				<h3>AUTOLOGOUS BLOOD TRANSFUSION</h3>
                <p>Autologous blood transfusion refers to transfusion of an individual’s own blood which has been withdrawn and stored. Autologous transfusion is done under the following situations:</p>
                <p>For elective surgery,</p>
				<p>During surgery,and Some sports persons.</p>
            </div>
            <div class="media-area">
                <img src="https://www.nhlbi.nih.gov/sites/default/files/2023-06/Whole-Blood-Transfusion-Parts_Social-Media-Animated-GIF_0.gif" alt=" ">
            </div>
        </div>

        <div class="slide" data-narration="Thank you for watching. Have a nice day. See you next lecture.">
            <div class="content-area">
                <h2>Thank You for Watching.</h2>
                <p></p>
                <p></p>
            </div>
            <div class="media-area">
                <img src="https://c.tenor.com/d3aJxAQpRNMAAAAC/giving-blood-blood.gif" alt="">
            </div>
        </div>

        </div>

    <div class="controls">
        <button id="prev-btn" disabled>← Previous</button>
        <button id="tts-btn">▶ Play Narration</button>
        <button id="next-btn">Next →</button>
        <button id="fullscreen-btn">⤡ Fullscreen</button>
    </div>

    <script>
        const slides = document.querySelectorAll('.slide');
        const prevBtn = document.getElementById('prev-btn');
        const nextBtn = document.getElementById('next-btn');
        const ttsBtn = document.getElementById('tts-btn');
        const fullscreenBtn = document.getElementById('fullscreen-btn');
        let currentSlideIndex = 0;

        /**
         * Speech Synthesis (TTS) Functions
         */
        const synth = window.speechSynthesis;
        let utterance = null;
        let isSpeaking = false;

        function speakNarration(text) {
            if (synth.speaking) {
                synth.cancel();
            }

            utterance = new SpeechSynthesisUtterance(text);
            utterance.lang = 'en-US';

            utterance.onstart = () => {
                isSpeaking = true;
                ttsBtn.textContent = '⏸ Pause Narration';
            };

            utterance.onend = () => {
                isSpeaking = false;
                ttsBtn.textContent = '▶ Play Narration';
            };

            synth.speak(utterance);
        }

        function toggleSpeech() {
            if (synth.speaking && isSpeaking) {
                synth.pause();
                isSpeaking = false;
                ttsBtn.textContent = '▶ Resume Narration';
            } else if (synth.paused) {
                synth.resume();
                isSpeaking = true;
                ttsBtn.textContent = '⏸ Pause Narration';
            } else {
                const narrationText = slides[currentSlideIndex].getAttribute('data-narration');
                if (narrationText) {
                    speakNarration(narrationText);
                }
            }
        }

        ttsBtn.addEventListener('click', toggleSpeech);


        /**
         * Navigation Functions
         */
        function showSlide(index) {
            // Stop TTS when changing slides
            if (synth.speaking) {
                synth.cancel();
                isSpeaking = false;
                ttsBtn.textContent = '▶ Play Narration';
            }

            // Hide all slides
            slides.forEach(slide => {
                slide.classList.remove('active');
            });

            // Show the current slide
            if (slides[index]) {
                slides[index].classList.add('active');
                currentSlideIndex = index;
            }

            // Update button states
            prevBtn.disabled = currentSlideIndex === 0;
            nextBtn.disabled = currentSlideIndex === slides.length - 1;
        }

        function nextSlide() {
            if (currentSlideIndex < slides.length - 1) {
                showSlide(currentSlideIndex + 1);
            }
        }

        function prevSlide() {
            if (currentSlideIndex > 0) {
                showSlide(currentSlideIndex - 1);
            }
        }

        nextBtn.addEventListener('click', nextSlide);
        prevBtn.addEventListener('click', prevSlide);


        /**
         * Fullscreen Function
         */
        function toggleFullscreen() {
            const elem = document.documentElement; // Target the whole document

            if (!document.fullscreenElement) {
                if (elem.requestFullscreen) {
                    elem.requestFullscreen();
                } else if (elem.webkitRequestFullscreen) { /* Safari */
                    elem.webkitRequestFullscreen();
                } else if (elem.msRequestFullscreen) { /* IE11 */
                    elem.msRequestFullscreen();
                }
            } else {
                if (document.exitFullscreen) {
                    document.exitFullscreen();
                } else if (document.webkitExitFullscreen) { /* Safari */
                    document.webkitExitFullscreen();
                } else if (document.msExitFullscreen) { /* IE11 */
                    document.msExitFullscreen();
                }
            }
        }

        fullscreenBtn.addEventListener('click', toggleFullscreen);

        // Initial setup
        showSlide(currentSlideIndex);

    </script>
</body>
</html>

