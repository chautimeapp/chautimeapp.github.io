# chautimeapp.github.io

*** DESIGN DECISIONS ***

Overall Goal:

An app for creating captivating recipes through a media-focused platform rather than mere text, and a user-friendly design without skimping on modern aesthetics.

We wanted an app that was:
1. simple to use - low maintenance and little editing required,
2. ergonomic in a kitchen environment, and
3. aesthetically appealing - something worthy of housing the recipes my mom had mastered.

Organization:
- focused on a straightforward and intuitive layout
- a primary recipebook to house all recipes
- a drafts folder for novel recipes in the making
- the ability for users to curate their own books

Recipe Creation:
- as close of a layout as possible to recipe viewing, in order for the user to have a realistic feel of the recipe view experience
- the ability to edit recipe books once completed, for those who want to revisit notes, add more to their recipes, or develope their own novel creations

Recipe Viewing:
- an initial preview page showing the final outcome, full ingredient list, brief step description, time required, and number of servings
- a page layout for each step, such that users have full focus on media steps, along with the ingredients and ingredient amounts used during that step so users aren't required to swipe back to remember ingredient specs
- a swipe-up-to-view full recipe page readily available in the case that someone wanted to see a full recipe preview

Sharing Recipes:
- a way to share media-focused recipes across a smaller platform to friends and loved ones. The intent is not for this to be a social-media focused app; rather, one shared amongst close family and friends
- this will be done through Apple's Messages App, and possibly via a hardcopy reformatting of a recipe for those more traditional


*** TECHNOLOGY ***

SwiftUI

UIKit

PhotosUI

AVFoundation

Google Sign-In


*** MOTIVATION ***

Growing up, I had always hoped for a method of storing my mother's traditional Cambodian recipes.

I pondered, how could I convince my busy mother to somehow get me a copy of her recipes? Handwritten cards? A Blog or Vlog? An Infographic? I threw all of these ideas at her over the years, but in the end none of them really stuck.

She always told me that the best way for me to learn would be to follow her around the kitchen - there were just too many minute details, on-the-fly suggestions, and alternatives for her to even try to keep track of in some form of written documentation.

Then came my mom's rediscovery of Facebook - and my realization that she is a lover of quick, vlog-style livestreams and picture documentation and sharing. To be able to verbally explain and showcase without much editing or the extra need of writing every detail in text, and to have a visual documentation of the fruits of her labour was what brought her back to using Facebook. Why not create an app for her to use to do exactly that for recipes, with a more personal domain?
