---
layout: post
title:      "Pirate Rekon AWS Rekognition and Cloudinary."
date:       2020-06-16 13:27:44 -0400
permalink:  pirate_rekon_aws_rekognition_and_cloudinary
---

A Sinatra based application. Amazon web services offer a variety of SDK's for utilization in web and mobile applications. The ability to access these from Ruby is easier than ever with the thorough documentation and examples found within any given product.  
	
	 Cloudinary, an easy to use cloud storage platform can be used in conjunction with any AWS service to easily scale any application. Amazon web services froths point forward known as AWS also offers a cloud platform for storage but the ease of Cloudinary put it over AWS in my opinion. Pirate Rekon was born from a marriage of the two.
	
   My thoughts behind Pirate Rekon arose from the string of mail thefts that have plagued the bay area California the last year. It seemed as though the authorities were at loss in deterring, apprehending and if an arrest was made it was only made after an expensive stakeout. This problem was one of scale. There were many perpetrators, systematically moving from area to area, locals, and local youth. With nearly every household having some sort of video surveillance, be it Ring, Nest, or private DVR the ability to ascertain the identities some of these thieves, even if the product  wasn’t be used in a prosecution. With individual households selectively participating in this product we can slowly understand the full scope and ultimately solution to this problem.
	 
  AWS Rekognition is the engine behind this application. It is not perfect. That said, the ability to train a model based on local parameters make it an interesting starting off point. Communities can over time develop an individualized model, making it easy to identify serial offenders and local youths. A relatively easy read document from AWS and Rekognition help to integrate Ruby with the API. 
Cloudinary a straight forward cloud storage platform allows a user to store, transform, and retrieve images, in this case jpeg and png format, with a handy URL. 

   Pirate Rekon is a unique application in that it can perform recognition tasks quickly over large datasets. This is accomplished with its in house algorithm. Processing first in app a possible, probable or negative return the user gets a quick assessment in any given case. If then a further examination is requested or desired a further call to the api will exhaustively examine the image against all others. By no means is this pre-examination an added layer of certainty in any one case and its development is on going. 
	 
   It should be stated the use and goals of this application are not to necessarily seek and demand prosecution but to identify. Individuals that know their identity is known and will be quickly known in any further incidents are far less likely to commit again. Its a community shaming, which can be proceeded with forgiveness, rehabilitation and reintegration. Understanding the scope will help to understand the underlying conditions and hopefully a community derived solution.     
