# Fishbl
A custom 3D-modeled helix desk toy for marbles themed around fishes.

My desk is always super messy and I struggle to find things to do when I'm really bored (other than just scrolling...), so I made this desk toy that is just the right amount of satisfaction! It's not so much like social media that you get addicted, but not too little that you give up on it quickly. After watching several marble runs on Youtube, I found that the helix portion was perfect for me (watching the marbles go in loops really gets you entranced). I also wanted to add customization for the user as well, so that each person would have different Fishbls and can rearrange it however they like! Making this project taught me a LOT of tools and fundamentals of CAD while still being beginner-friendly, so I'd recommend it for anybody trying to build something similar.

<img width="427" height="769" alt="Cover" src="https://github.com/user-attachments/assets/361a3c4b-a45e-4877-b782-3a845089fe56" />

## Summary
This 3D model was designed in **Onshape**. It was sliced in **BambuStudio**. Sign up for Onshape or another CAD that is compatible and import the following files!
|File|What's inside?|
|---|---|
|fishbleditable.step|contains the editable CAD file|
|fishbltower.3mf|contains the printable file for the tower|
|fishblextra.3mf|contains the printable file for charms, base, and stoppers|
|bomusers.csv|bill of materials for general users (not for Half Life)|
|BOM.csv|bill of materials for Half Life regarding the grant|

## Features
* A spiral/helix marble track
* Lots of customizable fish charms, including: sardine, clownfish, pufferfish, starfish, etc.
* 5 3d-printable marbles
* Magnet holes embedded into charms and pole
* Push buttons and stoppers for pushing multiple marbles at once

## Track & Pole
The track was made by sweeping the sketch of the edge, and the following line is a simple helix that spirals across a central pole. The pole in the middle is 10 cm across and also features a star indent on the top, which was made using sketches and extruding. On the very ends of the track, there are troughs that are not angled so that marbles can rest there without falling due to gravity. It also uses the same method as for making the main track, by extruding the sketch. However, the ends of the track are slightly angled, so I had to connect them using a face-to-face extrusion. On the pole, there are magnet holes that are dotted across the surface, made using wrapping and extruding.

<img width="188" height="378" alt="image" src="https://github.com/user-attachments/assets/015e981c-6c56-4695-8871-cd52aa7deb54" />

## Stoppers 
On the ends of the tracks are stoppers that are shaped like stars, meant to prevent the marbles from rolling off the end of the track. This is pretty self explanatory for the bottom trough, since you probably don't want 5 marbles running all over your desk! 

<img width="344" height="236" alt="image" src="https://github.com/user-attachments/assets/ae00bab9-9a66-4318-b2b5-3eb0b973c3b2" />

On the top trough, the stopper has a simple push mechanism on it that will push multiple marbles at once. A hole was put into the star, and a rod was made that was the exact diameter (though a few extra millimeters for tolerance). Then, circle stoppers at the ends were added so that the rod wouldn't go straight through the hole when you press it.

<img width="528" height="358" alt="image" src="https://github.com/user-attachments/assets/d6d94d8c-815c-4dcd-9239-0a2a4add5289" />

## Charms
The list of charms are as follows:
* Big Fish
* Small Fish
* Sardine
* Star
* Starfish
* Spiral Shell
* Clownfish
* Pufferfish

These charms were made using a variety of tools, such as fillet, mirror, coincident, and spline. The spheres located at the bottom are magnets. The charms also all feature 3 extrusion depths, so that the charm feels more 3D. Each charm has about 5 or 6 repeats, so that you can customize the tower however you like by connecting them with magnets. On the back of each charm, there are magnet holes to glue the magnets into. 

<img width="352" height="349" alt="image" src="https://github.com/user-attachments/assets/c3dae810-d9f6-4db4-bb8d-d9da38dcbb1a" />

The top section of smaller charms each only have 1 magnet, so it doesn't matter where you put them on the tower at all. 
However, the three bigger charms at the bottom have 2 magnets each (to allow for more stability), so they need to be put in specific sections of the tower where the magnets are measured correctly. Just look for areas where the magnet-holes are in-line with each other!

|<img width="464" height="257" alt="image" src="https://github.com/user-attachments/assets/4d285b1a-9d75-4757-acb3-4a102513be50"/>|<img width="378" height="282" alt="image" src="https://github.com/user-attachments/assets/09c6d908-6f66-4458-bc91-848f1481807a" />|
|---|---|

The whole theme of this project is fishes, and the tower is meant to look kind of like an aquarium with many fishes swimming about! 

## Slicing
As stated previously, this model was sliced in BambuStudio, and I have the plate set for the Bambu Lab A1 Mini. Because the tower is slightly too tall for the printer, I sliced it in half and arranged it on the corners so the tree supports wouldn't crash into each other (this took a lot of fiddling around because the towers are essentially the exact size for the plate). Additionally, there are two files because I couldn't fit everything onto just one plate. See the table in the summary for more details!

|<img width="706" height="751" alt="image" src="https://github.com/user-attachments/assets/d994eedd-15f7-4895-adb1-06f145eb4152" />|<img width="1084" height="676" alt="image" src="https://github.com/user-attachments/assets/d4d09b3b-2202-4039-8f43-6e89420ecc7b" />|
|---|---|

For printing, open up the .3mf files in BambuStudio (or other compatible software), and then slice it for your own 3D printer! I recommend using PLA for the filament type.

## Bill of Materials
|Part|Quantity|Price (USD)|Vendor|Link|
|---|---|---|---|---|
|Printing (PLA)|1|$32.50|Printing Legion (Hack Club)|https://app.slack.com/client/E09V59WQY1E/C083P4FJM46|
|5*2mm Magnets|1|$1.85|Temu|https://www.temu.com/ca/50-100-200pcs-5x2mm-round-small-magnet-n35-magnet-whiteboard-magnet-magnet-5-2mm-suitable-for-office-fridge-kitchen-5mm-x-2mm-g-601101898850933.html?_oak_mp_inf=EPXEnomv1ogBGiAyZDViMzJhZmE5Y2M0NjMwODY0NTE0ZWJkYzBiZDJmYyCL1dbqkzQ%3D&top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2Ffancy%2F6bf20472-bf8f-4709-8dc6-5f95d22019cf.jpg&spec_gallery_id=601101898850933&refer_page_sn=10032&freesia_scene=2&_oak_freesia_scene=2&_oak_rec_ext_1=MjM3&_oak_gallery_order=1940780989%2C305096788%2C1057903802%2C814925036%2C597470560&_oak_rec_ext_2=MjM3&_oak_rec_ext_3=Njg4&_oak_rec_sku=17602021861395&_oak_rec_ext_4=1831854169885859044&search_key=small%20magnet&refer_page_el_sn=200049&refer_page_name=goods&refer_page_id=10032_1792288331690_qbn9icvo14&_x_sessn_id=ur1tnftsy8|
|Gel Super Glue|1|$0.88|Dollarama|https://dollarama.instacart.com/store/dollarama/products/27058631-adhaero-thick-gel-super-glue-3-g|
|80 & 120 Grit Sandpaper|1|$0.35|Home Depot|https://www.homedepot.ca/product/everbilt-2-95-inch-x-4-92-inch-x-1-inch-dual-grit-80-120-fine-medium-sanding-sponge/1001942562|
|Filler Primer|1|$8.88|TG Store|https://tgstore.ca/products/kq462-automotive-filler-primer?variant=51307277287717&country=CA&currency=CAD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AU7gw4URmFMOGqa499MFSUJuuVvjuKM-fAgAOx2L9aUcWEAg2i1EvLpyRvo|
|Acrylic Paint|1|$3.36|Dollarama|https://dollarama.instacart.com/store/dollarama/products/27058703-artist-s-series-acrylic-paint-tubes-24-ct|
|Spray Matte Finish|1|$10.58|Walmart|http://walmart.ca/en/ip/Krylon-UV-Resistant-Clear-Coating-Matte-Clear-312-g/6000207323847|
|Taxes & Shipping|-|$17.13|-|-|
|Total|-|$75.53|-|-|

## Extra Notes [Half Life]
Note that, for the BOM cart screenshots submitted on the Half Life website, the prices are in CAD, not USD. All prices are converted from CAD to USD in the BOM individually, so there may be a very small rounding error in the total. The cart screenshots are also not entirely accurate for the following vendors:
* For Dollarama, the taxes are NOT included in the screenshot. This is because Dollarama requires you to purchase over $10.00 CAD worth of items when ordering online before it shows the full total including taxes. This restriction does not apply in-person, so it does not apply to me. However, the taxes are included in the BOM with the Ontario tax rate of 13%.
* For Walmart, the cart screenshot shows a pickup fee for the price being under $35. This does not apply to me because I will not be ordering online to reserve my item, but rather only go in-person. Please ignore the charge and only refer to the subtotal and taxes.

Furthermore, please pay attention to the descriptions of each item! Those that are labeled with [OUT OF POCKET] and [ALREADY OWNED] are not purchased with the grant and thus cost $0.01. Additionally, the vendors labeled (Local) are local to me, so I do not have to pay for shipping as I can go to them in person. All shipping prices are based on my own address and ability to go in-person for certain vendors. 

I'm excited to get building my Fishbl! This is probably the only week where I actually have at least a little bit of experience beforehand, so I put a LOT of effort into this and getting it the way I want! 
