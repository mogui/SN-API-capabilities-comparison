
##Social Network API Capabilities Comparison

| 							| Facebook	| Twitter	    | Youtube | Flickr   | 	Linkedin | Foursquare   | Gowalla | Instagram 
| : ----------------------- | :-------: | :-----------: | :-----: | :------: | :-------: | :----------: | :-----: | :-------: 
| Read Stream / Content		| x			| x			    | x		  | x		 | x		 | 	x		    | x	      | x	      
| Post Status / Text		| x			| x			    | 		  | 		 | x		 | 	x		    | x	      | 	      
| Like/Favourite Content	| x			| x			    | x		  | x		 | x		 | 			    | 	      | x	      
| Comment content			| x			| 			    | x		  | x		 | x		 | 	x		    | x	      | x	      
| Post/Upload Photo			| x			| 			    | 		  | x		 | 			 | x		    | 	      | x	      
| Post Video				| x			| 			    | x		  | 		 | 			 | 			    | 	      |           
| Read Geolocated content	| x			| x			    | x^4	  | x		 | 			 | x		    | x	      | x	      
| Post Geolocated content	| x			| x			    | x		  | x		 | 			 | x		    | x	      | x	      
| Read Direct Messages		| x			| x			    | x		  | 		 | x		 | 			    | 	      | 	      
| Post Direct Messages		| x			| -^3		    | x		  | 		 | x		 | 			    | 	      | 	                    	
| Real-Time Notification	| x^1		| x			    | 		  | 		 | 			 | x		    | x	      | x	      
| Manage Friends/Followers	| -^2		| x			    | 		  | 		 | 			 | x		    | 	      | x	      
| request limit				| -			| 350/h x Oauth | 	-	  | 	-	 | ND		 | 500/h x Oaut | 5/s x APP | -	      
                                                                                                                              

[1] via subscription,  it requires a callback [link](http://developers.facebook.com/docs/api/realtime/)

[2] just send request via fbml button [ref](http://stackoverflow.com/questions/4313013/facebook-friend-request-apis) not sure if it works

[3] For now it isn't possible they are releasing [new API for this](http://developers.facebook.com/docs/reference/api/message/)

[4] [ref](http://code.google.com/intl/it-IT/apis/youtube/2.0/reference.html#locationsp)   
