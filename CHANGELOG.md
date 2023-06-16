0.0.7 :
+ disallow nsfw content 

0.0.6 :
+ improve model loading (should improve performance after fist image).
+ investigate implementation of invisible wattermark (not convinced/reliable enough yet - commented).

0.0.5 :

+ add options for face restoration and upscaling. Not to sure about the reliability of visibility factor. Keep it to 1 if any doubt.

0.0.4 :

+ add upscaler option (does not as well as extra tab - will investigate)
+ add a models/FaceWap dir in sd

0.0.3 : 

+ Add options to select when swapping occur in img2img (before/after generation or both) 
+ Add a model selection (not very useful since it seems insightface has no plans to release further swapping models.)

0.0.2 : Reduce det_size in swapper when face is not found. Should improve results when face is too big.

0.0.1 : first release