MultipleOutputFormat
====================

Example to demonstrate how to write multiple outputs 

in this example we will write  output in seperate files based on our sample data.

here is our comma seperated sample data of customers we will take the sample data and write to the output based on the region of the customer


customer no,customer name,region,company



9899821411,"Burke, Honorato U.",Alaska,Eu Incorporated
9899821422,"Bell, Emily R.",Arizona,Ut Eros Non Company
9899821379,"Hewitt, Chelsea Y.",PA,Egestas Aliquam Fringilla LLP
9899821387,"Baldwin, Merrill H.",VT,Rhoncus Proin Corp.
9899821392,"Bradshaw, Uma H.",OH,Nam Nulla Associates
9899821453,"Pollard, Boris G.",Hawaii,Consequat Corp.
9899821379,"Avila, Velma D.",OR,Sodales LLC
9899821381,"Orr, James F.",Indiana,Sapien Imperdiet Ornare Corp.
9899821383,"Cooke, Paul W.",Alaska,Mollis Vitae Posuere Incorporated
9899821415,"Yates, Russell M.",Florida,Non Dui Nec Consulting
9899821379,"Morales, Maryam U.",AL,Nullam Feugiat Placerat Company
9899821371,"Paul, Brenna F.",Louisiana,Euismod Est Arcu LLP
9899821406,"Adkins, Demetrius J.",Wyoming,Nunc Ullamcorper Eu Limited
9899821456,"Rhodes, Gregory M.",DE,Dui Industries
9899821385,"Wood, Lamar W.",Pennsylvania,Vitae Aliquet Nec Limited
9899821413,"Montoya, Maile L.",NE,Vivamus Nisi Mauris LLC
9899821437,"Baldwin, Travis L.",VA,Eu Odio Company
9899821386,"Clarke, Keane D.",Oklahoma,Ut Pharetra Corp.
9899821405,"Armstrong, Mariam Z.",Delaware,Dolor LLC
9899821383,"Fulton, Cullen E.",OH,Et Ultrices LLC
9899821401,"Delaney, Chantale M.",CO,Vel LLP
9899821454,"Foster, Warren W.",Kentucky,Volutpat Nulla Dignissim Associates
9899821440,"Moran, Yoshi A.",OH,Amet Institute
9899821389,"Webb, Finn L.",GA,Duis Ac Arcu Company
9899821463,"Mclean, Kylee F.",Kentucky,Ligula Nullam PC
9899821439,"Holland, Kasper I.",NE,Rutrum Non PC
9899821374,"Watts, Denise A.",Ohio,Dolor Nulla Semper Incorporated
9899821410,"Mason, Wayne A.",Pennsylvania,Dolor Limited
9899821393,"Swanson, Vivian R.",Arizona,Pellentesque Inc.
9899821422,"Maxwell, Pearl M.",Alabama,Quis Diam Luctus Inc.
9899821373,"Craig, Helen P.",MN,Quisque Varius Limited
9899821401,"Robinson, Hillary F.",Illinois,Lobortis PC
9899821434,"Berger, Jarrod F.",Kentucky,Nunc In At LLP
9899821413,"Spence, Stone Q.",Oklahoma,Nostra Per Company
9899821460,"Mckenzie, Katell R.",AL,Vel Lectus Cum Foundation
9899821436,"Cantu, Mannix S.",Pennsylvania,Integer Tincidunt Aliquam Limited
9899821448,"Duke, Myles Q.",Maine,Curae; Industries
9899821425,"Moore, Nathaniel D.",AZ,Urna Nullam Associates
9899821449,"Hunter, Giacomo Y.",Colorado,Porttitor Company
9899821470,"Warner, Hayley G.",CA,Imperdiet Consulting
9899821375,"Jarvis, Chaim S.",ID,Tristique Company
9899821469,"Bridges, Palmer L.",Maine,At Augue Institute
9899821463,"Ratliff, Raya W.",AK,Consectetuer Corporation
9899821450,"Watkins, Ramona H.",Texas,Risus Donec Corp.
9899821397,"Sanders, Hyatt J.",Mississippi,Molestie Tortor Nibh Limited
9899821467,"Calderon, Astra S.",Michigan,Libero Est Congue Ltd
9899821456,"Allen, Zenia V.",OH,Hendrerit Corp.
9899821416,"Walsh, Eliana H.",UT,A Mi Institute
9899821426,"Whitfield, Halee R.",Alabama,Enim Associates
9899821453,"Bass, Signe V.",Arizona,Feugiat Nec Incorporated
9899821397,"Miles, Cally F.",Maryland,Libero At Company
9899821375,"Roman, Arsenio A.",MA,Enim Mi Tempor Industries
9899821438,"Rodriguez, Ezra S.",OK,Tellus Company
9899821452,"Stone, Jescie L.",Tennessee,Lectus Justo Eu Foundation
9899821382,"Francis, Katelyn X.",Arizona,Morbi Tristique Institute
9899821410,"Mcdonald, Grace E.",OK,Dui PC
9899821455,"Galloway, Alexis S.",Alaska,Quisque Purus Company
9899821414,"Albert, Serina T.",Ohio,Sed Libero Proin Associates
9899821453,"Skinner, Ignatius K.",Nevada,Maecenas Mi Corporation
9899821378,"Head, Tanya K.",Nebraska,Amet Metus LLP
9899821382,"Wright, Justine D.",WY,Lacinia Foundation
9899821424,"Butler, Brian K.",Alabama,Donec Tincidunt Incorporated
9899821378,"Emerson, Armando M.",Maryland,Enim Mi LLC
9899821375,"Vinson, Martha B.",Oregon,At Augue Id Institute
9899821386,"Crawford, Quintessa H.",Tennessee,Erat Company
9899821457,"Blackburn, Kenneth D.",TN,Sed Company
9899821451,"Cobb, Kameko T.",Utah,Ut Pharetra Industries
9899821413,"Tyler, Leroy Q.",DE,Neque Nullam Ut LLC
9899821462,"Harvey, Iliana Z.",ME,Dolor Elit Limited
9899821380,"Knowles, Linus H.",UT,Netus Et Inc.
9899821408,"Durham, Shana H.",NE,Cursus A LLC
9899821445,"Gould, Xena D.",Massachusetts,Nunc Id Enim Limited
9899821420,"Wiggins, Latifah A.",Florida,Massa Quisque Porttitor Corp.
9899821448,"Gibbs, Vernon A.",Alaska,Ipsum Corporation
9899821423,"Cotton, Jarrod X.",Arkansas,Sem Molestie Institute
9899821424,"Simpson, Carlos N.",Louisiana,Semper Associates
9899821443,"Flowers, Leslie B.",MO,Nisl Quisque Industries
9899821374,"Blevins, May G.",Kansas,Nulla Eu LLP
9899821431,"Dixon, Holmes L.",AR,Eleifend Cras Sed Corporation
9899821379,"Mathis, Haviva K.",Ohio,Mauris Vel Industries
9899821467,"Osborn, Ann B.",DE,Curae; Institute
9899821451,"Allison, Cedric B.",Arkansas,Velit Justo LLP
9899821447,"Kirkland, Peter I.",WI,Elit Limited
9899821378,"Mcleod, Doris U.",CA,Quisque Company
9899821436,"Reed, Isabella R.",Michigan,Placerat Velit Limited
9899821376,"Aguirre, Vladimir O.",MI,Mollis Ltd
9899821407,"Buckner, Dorothy Z.",MA,Nunc Industries
9899821434,"Wiley, Byron K.",UT,Dui Quis Accumsan Institute
9899821436,"Todd, Jennifer R.",Ohio,Eu Associates
9899821411,"Ewing, Hakeem N.",Vermont,Magnis Dis Consulting
9899821447,"Mccray, Allegra T.",ME,Turpis Nulla Corporation
9899821387,"Bonner, James B.",Alaska,Ante Inc.
9899821464,"Montoya, Breanna F.",OK,Euismod In Limited
9899821375,"Wilkerson, Zahir Q.",CO,Egestas Urna Justo Company
9899821423,"Foley, Regina P.",Virginia,Nunc Laoreet Lectus Institute
9899821409,"Malone, Erich A.",Louisiana,In Mi Company
9899821370,"Dale, Sophia Z.",KS,Non Leo LLC
9899821408,"Rosario, Hedwig R.",Maine,Fringilla Corp.
9899821389,"Roberts, Charles T.",VA,Arcu Consulting
9899821415,"Mitchell, Griffith R.",Arizona,Mauris Rhoncus PC
