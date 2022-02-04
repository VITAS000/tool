# Coverage comparison

We compare Vitas with random testing and Skillexplorer about the state space coverage, and the time limit is set as 10 minites for three techniques. The table below shows the state space coverage of each technique. Here, the manual test results are for reference because they have no time limit. The last column is the union of state space coverage of three techniques and users. We carry out this experiment on the benchmark. The skills selected here satisfy three conditions: 1. They can be opened by four methods. 2. Their behavior is consistent for four methods. 3. No network exception happens during the test.

To get the table below, run ```python experiment.py 7``` in the [experiment](tool/experiment.zip) directory. The table is saved in fig7_coverge_rate_four.xlsx.


|skill's name|manual|Vitas|random|Skillexplorer|union|
|------|------|------|------|------|------|
|Build a PC Sales|[15](comparison/user/Build_a_PC_Sales.txt)|[10](comparison/vitas/Build_a_PC_Sales.txt)|[14](comparison/random/Build_a_PC_Sales.txt)|[7](comparison/skillExplorer/Build a PC Sales.zip)|25|
|Asthma Device Helper|[8](comparison/user/Asthma_Device_Helper.txt)|[32](comparison/vitas/Asthma_Device_Helper.txt)|[32](comparison/random/Asthma_Device_Helper.txt)|[59](comparison/skillExplorer/Asthma Device Helper.zip)|61|
|Animal Sounds|[45](comparison/user/Animal_Sounds.txt)|[37](comparison/vitas/Animal_Sounds.txt)|[27](comparison/random/Animal_Sounds.txt)|[25](comparison/skillExplorer/Animal Sounds.zip)|108|
|Dr Speech|[14](comparison/user/Dr_Speech.txt)|[21](comparison/vitas/Dr_Speech.txt)|[12](comparison/random/Dr_Speech.txt)|[18](comparison/skillExplorer/Dr Speech.zip)|28|
|Song Quiz|[59](comparison/user/Song_Quiz.txt)|[33](comparison/vitas/Song_Quiz.txt)|[17](comparison/random/Song_Quiz.txt)|[15](comparison/skillExplorer/Song Quiz.zip)|89|
|Choose Your Adventure Game|[25](comparison/user/Choose_Your_Adventure_Game.txt)|[12](comparison/vitas/Choose_Your_Adventure_Game.txt)|[12](comparison/random/Choose_Your_Adventure_Game.txt)|[10](comparison/skillExplorer/Choose Your Adventure Game.zip)|26|
|Toe Tac Tic|[13](comparison/user/Toe_Tac_Tic.txt)|[13](comparison/vitas/Toe_Tac_Tic.txt)|[12](comparison/random/Toe_Tac_Tic.txt)|[23](comparison/skillExplorer/Toe Tac Tic.zip)|25|
|Butterball|[33](comparison/user/Butterball.txt)|[22](comparison/vitas/Butterball.txt)|[16](comparison/random/Butterball.txt)|[38](comparison/skillExplorer/Butterball.zip)|77|
|My Horoscope|[26](comparison/user/My_Horoscope.txt)|[39](comparison/vitas/My_Horoscope.txt)|[40](comparison/random/My_Horoscope.txt)|[18](comparison/skillExplorer/My Horoscope.zip)|82|
|Birthstone|[14](comparison/user/Birthstone.txt)|[16](comparison/vitas/Birthstone.txt)|[12](comparison/random/Birthstone.txt)|[9](comparison/skillExplorer/Birthstone.zip)|20|
|Cooking Temperature Buddy|[8](comparison/user/Cooking_Temperature_Buddy.txt)|[13](comparison/vitas/Cooking_Temperature_Buddy.txt)|[15](comparison/random/Cooking_Temperature_Buddy.txt)|[11](comparison/skillExplorer/Cooking Temperature Buddy.zip)|17|
|Yoga Teacher|[39](comparison/user/Yoga_Teacher.txt)|[30](comparison/vitas/Yoga_Teacher.txt)|[14](comparison/random/Yoga_Teacher.txt)|[10](comparison/skillExplorer/Yoga Teacher.zip)|48|
|NewsChest: Unofficial FC Barcelona news|[16](comparison/user/NewsChest_Unofficial_FC_Barcelona_news.txt)|[11](comparison/vitas/NewsChest_Unofficial_FC_Barcelona_news.txt)|[13](comparison/random/NewsChest_Unofficial_FC_Barcelona_news.txt)|[8](comparison/skillExplorer/NewsChest  Unofficial FC Barcelona news.zip)|29|
|Super Tech Support|[10](comparison/user/Super_Tech_Support.txt)|[19](comparison/vitas/Super_Tech_Support.txt)|[16](comparison/random/Super_Tech_Support.txt)|[19](comparison/skillExplorer/Super Tech Support.zip)|19|
|Unofficial Simpson's Quote Finder|[8](comparison/user/Unofficial_Simpson_s_Quote_Finder.txt)|[9](comparison/vitas/Unofficial_Simpson_s_Quote_Finder.txt)|[9](comparison/random/Unofficial_Simpson_s_Quote_Finder.txt)|[8](comparison/skillExplorer/Unofficial Simpson s Quote Finder.zip)|9|
|Funny Noises|[9](comparison/user/Funny_Noises.txt)|[11](comparison/vitas/Funny_Noises.txt)|[11](comparison/random/Funny_Noises.txt)|[11](comparison/skillExplorer/Funny Noises.zip)|11|
|Actor Wiki|[10](comparison/user/Actor_Wiki.txt)|[11](comparison/vitas/Actor_Wiki.txt)|[10](comparison/random/Actor_Wiki.txt)|[14](comparison/skillExplorer/Actor Wiki.zip)|29|
|LOST Geek Quiz|[70](comparison/user/LOST_Geek_Quiz.txt)|[98](comparison/vitas/LOST_Geek_Quiz.txt)|[85](comparison/random/LOST_Geek_Quiz.txt)|[17](comparison/skillExplorer/LOST Geek Quiz.zip)|180|
|Grace Chapel|[16](comparison/user/Grace_Chapel.txt)|[17](comparison/vitas/Grace_Chapel.txt)|[15](comparison/random/Grace_Chapel.txt)|[17](comparison/skillExplorer/Grace Chapel.zip)|28|
|Scare off Burglars|[6](comparison/user/Scare_off_Burglars.txt)|[10](comparison/vitas/Scare_off_Burglars.txt)|[10](comparison/random/Scare_off_Burglars.txt)|[9](comparison/skillExplorer/Scare off Burglars.zip)|15|
|NPR|[9](comparison/user/NPR.txt)|[14](comparison/vitas/NPR.txt)|[13](comparison/random/NPR.txt)|[8](comparison/skillExplorer/NPR.zip)|19|
|Soccer Scores|[6](comparison/user/Soccer_Scores.txt)|[10](comparison/vitas/Soccer_Scores.txt)|[6](comparison/random/Soccer_Scores.txt)|[3](comparison/skillExplorer/Soccer Scores.zip)|12|
|The Answer Chicago|[2](comparison/user/The_Answer_Chicago.txt)|[2](comparison/vitas/The_Answer_Chicago.txt)|[2](comparison/random/The_Answer_Chicago.txt)|[1](comparison/skillExplorer/The Answer Chicago.zip)|2|
|FireBoard - Cloud Connected Smart Thermometer|[5](comparison/user/FireBoard_Cloud_Connected_Smart_Thermometer.txt)|[7](comparison/vitas/FireBoard_Cloud_Connected_Smart_Thermometer.txt)|[7](comparison/random/FireBoard_Cloud_Connected_Smart_Thermometer.txt)|[7](comparison/skillExplorer/FireBoard - Cloud Connected Smart Thermometer.zip)|7|
|Travel Dates|[3](comparison/user/Travel_Dates.txt)|[4](comparison/vitas/Travel_Dates.txt)|[5](comparison/random/Travel_Dates.txt)|[5](comparison/skillExplorer/Travel Dates.zip)|8|
|Pico y Placa|[23](comparison/user/Pico_y_Placa.txt)|[7](comparison/vitas/Pico_y_Placa.txt)|[8](comparison/random/Pico_y_Placa.txt)|[11](comparison/skillExplorer/Pico y Placa.zip)|24|
|I am Affirmations|[36](comparison/user/I_am_Affirmations.txt)|[21](comparison/vitas/I_am_Affirmations.txt)|[18](comparison/random/I_am_Affirmations.txt)|[13](comparison/skillExplorer/I am Affirmations.zip)|52|
|The Rock of Northeast Arkansas|[15](comparison/user/The_Rock_of_Northeast_Arkansas.txt)|[19](comparison/vitas/The_Rock_of_Northeast_Arkansas.txt)|[22](comparison/random/The_Rock_of_Northeast_Arkansas.txt)|[18](comparison/skillExplorer/The Rock of Northeast Arkansas.zip)|25|
|Lighthouse Apostolic Ministries, Saint Louis, MO|[15](comparison/user/Lighthouse_Apostolic_Ministries_Saint_Louis_MO.txt)|[15](comparison/vitas/Lighthouse_Apostolic_Ministries_Saint_Louis_MO.txt)|[22](comparison/random/Lighthouse_Apostolic_Ministries_Saint_Louis_MO.txt)|[17](comparison/skillExplorer/Lighthouse Apostolic Ministries, Saint Louis, MO.zip)|23|
|Fitness Encouragement|[69](comparison/user/Fitness_Encouragement.txt)|[28](comparison/vitas/Fitness_Encouragement.txt)|[21](comparison/random/Fitness_Encouragement.txt)|[16](comparison/skillExplorer/Fitness Encouragement.zip)|80|
|A path to forgiveness|[48](comparison/user/A_path_to_forgiveness.txt)|[52](comparison/vitas/A_path_to_forgiveness.txt)|[44](comparison/random/A_path_to_forgiveness.txt)|[51](comparison/skillExplorer/A path to forgiveness.zip)|54|
|Driving Etiquette|[62](comparison/user/Driving_Etiquette.txt)|[11](comparison/vitas/Driving_Etiquette.txt)|[8](comparison/random/Driving_Etiquette.txt)|[5](comparison/skillExplorer/Driving Etiquette.zip)|69|
|cook perfect eggs|[63](comparison/user/cook_perfect_eggs.txt)|[39](comparison/vitas/cook_perfect_eggs.txt)|[31](comparison/random/cook_perfect_eggs.txt)|[61](comparison/skillExplorer/cook perfect eggs.zip)|88|
|Dracula Gossip|[3](comparison/user/Dracula_Gossip.txt)|[20](comparison/vitas/Dracula_Gossip.txt)|[12](comparison/random/Dracula_Gossip.txt)|[17](comparison/skillExplorer/Dracula Gossip.zip)|33|
|Never Have I Ever|[35](comparison/user/Never_Have_I_Ever.txt)|[25](comparison/vitas/Never_Have_I_Ever.txt)|[22](comparison/random/Never_Have_I_Ever.txt)|[28](comparison/skillExplorer/Never Have I Ever.zip)|68|
|Unofficial Cash4Life Winning Numbers|[22](comparison/user/Unofficial_Cash4Life_Winning_Numbers.txt)|[28](comparison/vitas/Unofficial_Cash4Life_Winning_Numbers.txt)|[17](comparison/random/Unofficial_Cash4Life_Winning_Numbers.txt)|[19](comparison/skillExplorer/Unofficial Cash4Life Winning Numbers.zip)|44|
|Backgammon Helper|[21](comparison/user/Backgammon_Helper.txt)|[29](comparison/vitas/Backgammon_Helper.txt)|[27](comparison/random/Backgammon_Helper.txt)|[29](comparison/skillExplorer/Backgammon Helper.zip)|38|
|India trivia game|[53](comparison/user/India_trivia_game.txt)|[65](comparison/vitas/India_trivia_game.txt)|[44](comparison/random/India_trivia_game.txt)|[22](comparison/skillExplorer/India trivia game.zip)|119|
|Santa's Helper|[85](comparison/user/Santa_s_Helper.txt)|[47](comparison/vitas/Santa_s_Helper.txt)|[21](comparison/random/Santa_s_Helper.txt)|[74](comparison/skillExplorer/Santa s Helper.zip)|188|
|Magic Pet|[95](comparison/user/Magic_Pet.txt)|[35](comparison/vitas/Magic_Pet.txt)|[32](comparison/random/Magic_Pet.txt)|[29](comparison/skillExplorer/Magic Pet.zip)|157|
|World Languages|[61](comparison/user/World_Languages.txt)|[73](comparison/vitas/World_Languages.txt)|[49](comparison/random/World_Languages.txt)|[17](comparison/skillExplorer/World Languages.zip)|133|
|Seventh Inning Stretch Baseball - Buttons Optional|[53](comparison/user/Seventh_Inning_Stretch_Baseball_Buttons_Optional.txt)|[40](comparison/vitas/Seventh_Inning_Stretch_Baseball_Buttons_Optional.txt)|[41](comparison/random/Seventh_Inning_Stretch_Baseball_Buttons_Optional.txt)|[15](comparison/skillExplorer/Seventh Inning Stretch Baseball - Buttons Optional.zip)|80|
|Hurricane Center|[65](comparison/user/Hurricane_Center.txt)|[49](comparison/vitas/Hurricane_Center.txt)|[31](comparison/random/Hurricane_Center.txt)|[48](comparison/skillExplorer/Hurricane Center.zip)|93|
|Stanley's journey|[57](comparison/user/Stanley_s_journey.txt)|[40](comparison/vitas/Stanley_s_journey.txt)|[32](comparison/random/Stanley_s_journey.txt)|[53](comparison/skillExplorer/Stanley s journey.zip)|65|
|Uninspiring Quotes|[20](comparison/user/Uninspiring_Quotes.txt)|[20](comparison/vitas/Uninspiring_Quotes.txt)|[8](comparison/random/Uninspiring_Quotes.txt)|[16](comparison/skillExplorer/Uninspiring Quotes.zip)|33|
|Travelers|unavailable|[4](comparison/vitas/Travelers.txt)|[10](comparison/random/Travelers.txt)|[10](comparison/skillExplorer/Travelers.zip)|14|
|U.S. Bank|unavailable|[14](comparison/vitas/U_S_Bank.txt)|[11](comparison/random/U_S_Bank.txt)|unavailable|16|
|IBKR IBot|unavailable|[37](comparison/vitas/IBKR_IBot.txt)|[37](comparison/random/IBKR_IBot.txt)|unavailable|48|
|Stock Info|unavailable|[19](comparison/vitas/Stock_Info.txt)|unavailable|[13](comparison/skillExplorer/Stock Info.zip)|26|
|electraFi.com|unavailable|unavailable|unavailable|unavailable|0|
|JW.ORG®|[26](comparison/user/JW_ORG_.txt)|[12](comparison/vitas/JW_ORG_.txt)|[12](comparison/random/JW_ORG_.txt)|unavailable|28|
|The Bible|unavailable|[16](comparison/vitas/The_Bible.txt)|[55](comparison/random/The_Bible.txt)|unavailable|71|
|Life Hacks|unavailable|[10](comparison/vitas/Life_Hacks.txt)|[6](comparison/random/Life_Hacks.txt)|[11](comparison/skillExplorer/Life Hacks.zip)|19|
|New vocabulary word|unavailable|[42](comparison/vitas/New_vocabulary_word.txt)|[22](comparison/random/New_vocabulary_word.txt)|[4](comparison/skillExplorer/New vocabulary word.zip)|60|
|Ehrlich Pest Control|unavailable|unavailable|[14](comparison/random/Ehrlich_Pest_Control.txt)|[33](comparison/skillExplorer/Ehrlich Pest Control.zip)|39|
|Today's special|unavailable|unavailable|unavailable|unavailable|0|
|Fox Chapel School Lunch|unavailable|[4](comparison/vitas/Fox_Chapel_School_Lunch.txt)|unavailable|unavailable|4|
|Recipe Finder By Ingredients|unavailable|[8](comparison/vitas/Recipe_Finder_By_Ingredients.txt)|[6](comparison/random/Recipe_Finder_By_Ingredients.txt)|[10](comparison/skillExplorer/Recipe Finder By Ingredients.zip)|16|
|Go Irish|unavailable|[2](comparison/vitas/Go_Irish.txt)|[2](comparison/random/Go_Irish.txt)|[2](comparison/skillExplorer/Go Irish.zip)|2|
|Freedom Festival|unavailable|[23](comparison/vitas/Freedom_Festival.txt)|unavailable|unavailable|23|
|Skyrim Very Special Edition|unavailable|[14](comparison/vitas/Skyrim_Very_Special_Edition.txt)|unavailable|unavailable|14|
|Beat the Intro|unavailable|[3](comparison/vitas/Beat_the_Intro.txt)|unavailable|unavailable|3|
|The Floor is Lava|unavailable|unavailable|[55](comparison/random/The_Floor_is_Lava.txt)|[37](comparison/skillExplorer/The Floor is Lava.zip)|84|
|Destiny 2 Ghost|unavailable|[18](comparison/vitas/Destiny_2_Ghost.txt)|unavailable|unavailable|18|
|Trivial Pursuit Tap|unavailable|[51](comparison/vitas/Trivial_Pursuit_Tap.txt)|unavailable|unavailable|51|
|Fortnite Skin Picker|unavailable|[16](comparison/vitas/Fortnite_Skin_Picker.txt)|[9](comparison/random/Fortnite_Skin_Picker.txt)|[12](comparison/skillExplorer/Fortnite Skin Picker.zip)|26|
|Simon Says|unavailable|[30](comparison/vitas/Simon_Says.txt)|[29](comparison/random/Simon_Says.txt)|[36](comparison/skillExplorer/Simon Says.zip)|95|
|My Capital Quiz|[10](comparison/user/My_Capital_Quiz.txt)|[inconsistent behavior](comparison/vitas/My_Capital_Quiz.txt)|[inconsistent behavior](comparison/random/My_Capital_Quiz.txt)|unavailable|10|
|Bender the Great|[13](comparison/user/Bender_the_Great.txt)|[22](comparison/vitas/Bender_the_Great.txt)|[21](comparison/random/Bender_the_Great.txt)|unavailable|32|
|Murder Mystery Theater|[44](comparison/user/Murder_Mystery_Theater.txt)|[27](comparison/vitas/Murder_Mystery_Theater.txt)|[19](comparison/random/Murder_Mystery_Theater.txt)|unavailable|48|
|Country Flag Quiz|unavailable|unavailable|unavailable|unavailable|0|
|Head Games|[50](comparison/user/Head_Games.txt)|[22](comparison/vitas/Head_Games.txt)|[12](comparison/random/Head_Games.txt)|unavailable|58|
|The Bingo Caller|unavailable|[21](comparison/vitas/The_Bingo_Caller.txt)|unavailable|[85](comparison/skillExplorer/The Bingo Caller.zip)|106|
|Naughty Or Nice Quiz|unavailable|unavailable|unavailable|[5](comparison/skillExplorer/Naughty Or Nice Quiz.zip)|5|
|Amazon Math|[2](comparison/user/Amazon_Math.txt)|unavailable|[2](comparison/random/Amazon_Math.txt)|unavailable|2|
|Escape mystery room|unavailable|unavailable|unavailable|unavailable|0|
|Trick or Treat|unavailable|[34](comparison/vitas/Trick_or_Treat.txt)|[13](comparison/random/Trick_or_Treat.txt)|[23](comparison/skillExplorer/Trick or Treat.zip)|60|
|Westworld Quotes|unavailable|unavailable|[3](comparison/random/Westworld_Quotes.txt)|unavailable|3|
|AYRIAL: Feng Shui Tips|unavailable|[11](comparison/vitas/AYRIAL_Feng_Shui_Tips.txt)|[10](comparison/random/AYRIAL_Feng_Shui_Tips.txt)|[17](comparison/skillExplorer/AYRIAL  Feng Shui Tips.zip)|32|
|Daily Horoscope|unavailable|[13](comparison/vitas/Daily_Horoscope.txt)|[5](comparison/random/Daily_Horoscope.txt)|unavailable|14|
|Cooking Temperatures|[24](comparison/user/Cooking_Temperatures.txt)|[22](comparison/vitas/Cooking_Temperatures.txt)|[22](comparison/random/Cooking_Temperatures.txt)|unavailable|26|
|Coffee Maker|unavailable|[30](comparison/vitas/Coffee_Maker.txt)|[20](comparison/random/Coffee_Maker.txt)|[13](comparison/skillExplorer/Coffee Maker.zip)|38|
|Daily Gemini Horoscope|[11](comparison/user/Daily_Gemini_Horoscope.txt)|[13](comparison/vitas/Daily_Gemini_Horoscope.txt)|unavailable|unavailable|20|
|Fortune Teller|unavailable|[13](comparison/vitas/Fortune_Teller.txt)|[14](comparison/random/Fortune_Teller.txt)|[11](comparison/skillExplorer/Fortune Teller.zip)|33|
|Daily Pisces Horoscope|[11](comparison/user/Daily_Pisces_Horoscope.txt)|[16](comparison/vitas/Daily_Pisces_Horoscope.txt)|[12](comparison/random/Daily_Pisces_Horoscope.txt)|unavailable|29|
|Allrecipes|unavailable|unavailable|unavailable|[23](comparison/skillExplorer/Allrecipes.zip)|23|
|The Audio Chef|unavailable|[21](comparison/vitas/The_Audio_Chef.txt)|[13](comparison/random/The_Audio_Chef.txt)|unavailable|32|
|Baby Gender Reveal Themes|unavailable|unavailable|[13](comparison/random/Baby_Gender_Reveal_Themes.txt)|[59](comparison/skillExplorer/Baby Gender Reveal Themes.zip)|72|
|Grandmother Names|[1](comparison/user/Grandmother_Names.txt)|[inconsistent behavior](comparison/vitas/Grandmother_Names.txt)|[inconsistent behavior](comparison/random/Grandmother_Names.txt)|unavailable|1|
|Guest Reception|unavailable|[43](comparison/vitas/Guest_Reception.txt)|[31](comparison/random/Guest_Reception.txt)|unavailable|65|
|Utah Jazz|unavailable|[31](comparison/vitas/Utah_Jazz.txt)|unavailable|unavailable|31|
|48 Laws of Power|unavailable|[21](comparison/vitas/48_Laws_of_Power.txt)|[51](comparison/random/48_Laws_of_Power.txt)|[22](comparison/skillExplorer/48 Laws of Power.zip)|84|
|I spilt lipstick in your Valentino bag|unavailable|[26](comparison/vitas/I_spilt_lipstick_in_your_Valentino_bag.txt)|[4](comparison/random/I_spilt_lipstick_in_your_Valentino_bag.txt)|unavailable|30|
|Halloween Jokes|unavailable|[32](comparison/vitas/Halloween_Jokes.txt)|[16](comparison/random/Halloween_Jokes.txt)|[18](comparison/skillExplorer/Halloween Jokes.zip)|61|
|Rain Storm for Healing|unavailable|[8](comparison/vitas/Rain_Storm_for_Healing.txt)|[3](comparison/random/Rain_Storm_for_Healing.txt)|[6](comparison/skillExplorer/Rain Storm for Healing.zip)|15|
|U.S. Postal Service® Informed Delivery®|unavailable|[1](comparison/vitas/U_S_Postal_Service_Informed_Delivery_.txt)|[1](comparison/random/U_S_Postal_Service_Informed_Delivery_.txt)|unavailable|1|
|Smart Home|unavailable|[9](comparison/vitas/Smart_Home.txt)|[5](comparison/random/Smart_Home.txt)|[8](comparison/skillExplorer/Smart Home.zip)|12|
|Good Vibes|unavailable|unavailable|[7](comparison/random/Good_Vibes.txt)|[2](comparison/skillExplorer/Good Vibes.zip)|9|
|Chat Bot|[1](comparison/user/Chat_Bot.txt)|unavailable|[inconsistent behavior](comparison/random/Chat_Bot.txt)|[inconsistent behavior](comparison/skillExplorer/Chat Bot.zip)|1|
|ha ha burns|unavailable|unavailable|unavailable|unavailable|0|
|My Speaker|unavailable|[19](comparison/vitas/My_Speaker.txt)|unavailable|unavailable|19|
|My Metronome|unavailable|[13](comparison/vitas/My_Metronome.txt)|unavailable|unavailable|13|
|Casey Neistat|unavailable|[37](comparison/vitas/Casey_Neistat.txt)|[26](comparison/random/Casey_Neistat.txt)|unavailable|46|
|Circle of Fifths Facts|unavailable|[12](comparison/vitas/Circle_of_Fifths_Facts.txt)|[6](comparison/random/Circle_of_Fifths_Facts.txt)|[6](comparison/skillExplorer/Circle of Fifths Facts.zip)|20|
|The Weather Channel|unavailable|[6](comparison/vitas/The_Weather_Channel.txt)|unavailable|[4](comparison/skillExplorer/The Weather Channel.zip)|9|
|Parkview Christian Church Homer Glen Campus|[16](comparison/user/Parkview_Christian_Church_Homer_Glen_Campus.txt)|unavailable|[22](comparison/random/Parkview_Christian_Church_Homer_Glen_Campus.txt)|unavailable|24|
|SaiSkill|[8](comparison/user/SaiSkill.txt)|unavailable|[6](comparison/random/SaiSkill.txt)|unavailable|13|
|The Rookie's Guide to the NFL|unavailable|unavailable|unavailable|[2](comparison/skillExplorer/The Rookie s Guide to the NFL.zip)|2|
|Share The Facts|[7](comparison/user/Share_The_Facts.txt)|unavailable|[6](comparison/random/Share_The_Facts.txt)|unavailable|7|
|LaMetric TIME – connected clock for smart home|[14](comparison/user/LaMetric_TIME_connected_clock_for_smart_home.txt)|unavailable|[16](comparison/random/LaMetric_TIME_connected_clock_for_smart_home.txt)|[15](comparison/skillExplorer/LaMetric TIME – connected clock for smart home.zip)|17|
|Vivitar Home Cameras|unavailable|[1](comparison/vitas/Vivitar_Home_Cameras.txt)|[1](comparison/random/Vivitar_Home_Cameras.txt)|[1](comparison/skillExplorer/Vivitar Home Cameras.zip)|1|
|Adventure Game|[70](comparison/user/Adventure_Game.txt)|unavailable|[inconsistent behavior](comparison/random/Adventure_Game.txt)|unavailable|70|
|3 Cards|[17](comparison/user/3_Cards.txt)|[17](comparison/vitas/3_Cards.txt)|unavailable|[14](comparison/skillExplorer/3 Cards.zip)|21|
|Ten Pin Bowling|unavailable|[49](comparison/vitas/Ten_Pin_Bowling.txt)|[53](comparison/random/Ten_Pin_Bowling.txt)|[43](comparison/skillExplorer/Ten Pin Bowling.zip)|72|
|The Shocking Truth|unavailable|unavailable|unavailable|unavailable|0|
|66 Tolls|[14](comparison/user/66_Tolls.txt)|unavailable|[14](comparison/random/66_Tolls.txt)|unavailable|17|
|Magnificent Facts|[16](comparison/user/Magnificent_Facts.txt)|unavailable|[11](comparison/random/Magnificent_Facts.txt)|[19](comparison/skillExplorer/Magnificent Facts.zip)|23|
|Explain like I'm five|[6](comparison/user/Explain_like_I_m_five.txt)|unavailable|unavailable|unavailable|6|
|My Quest To Teach|[78](comparison/user/My_Quest_To_Teach.txt)|unavailable|[17](comparison/random/My_Quest_To_Teach.txt)|unavailable|92|
|Beer Bot|[3](comparison/user/Beer_Bot.txt)|[inconsistent behavior](comparison/vitas/Beer_Bot.txt)|[inconsistent behavior](comparison/random/Beer_Bot.txt)|[inconsistent behavior](comparison/skillExplorer/Beer Bot.zip)|3|
|Park Creek Menu|[3](comparison/user/Park_Creek_Menu.txt)|[inconsistent behavior](comparison/vitas/Park_Creek_Menu.txt)|unavailable|[3](comparison/skillExplorer/Park Creek Menu.zip)|4|
|Wine Down|[69](comparison/user/Wine_Down.txt)|[49](comparison/vitas/Wine_Down.txt)|[28](comparison/random/Wine_Down.txt)|unavailable|74|
|All Cats|unavailable|unavailable|[7](comparison/random/All_Cats.txt)|unavailable|7|
|This Day in History|unavailable|[45](comparison/vitas/This_Day_in_History.txt)|unavailable|[47](comparison/skillExplorer/This Day in History.zip)|89|
|Crisis Response|[162](comparison/user/Crisis_Response.txt)|unavailable|[85](comparison/random/Crisis_Response.txt)|unavailable|240|
|Mayor Karen Best|unavailable|[39](comparison/vitas/Mayor_Karen_Best.txt)|[33](comparison/random/Mayor_Karen_Best.txt)|[50](comparison/skillExplorer/Mayor Karen Best.zip)|68|
|Recommend a Romance Author|[20](comparison/user/Recommend_a_Romance_Author.txt)|unavailable|[13](comparison/random/Recommend_a_Romance_Author.txt)|[14](comparison/skillExplorer/Recommend a Romance Author.zip)|28|
|Rock Paper Scissors|[62](comparison/user/Rock_Paper_Scissors.txt)|[20](comparison/vitas/Rock_Paper_Scissors.txt)|[33](comparison/random/Rock_Paper_Scissors.txt)|[inconsistent behavior](comparison/skillExplorer/Rock Paper Scissors.zip)|102|
|Treasure Words|unavailable|[19](comparison/vitas/Treasure_Words.txt)|[10](comparison/random/Treasure_Words.txt)|[17](comparison/skillExplorer/Treasure Words.zip)|33|
|Creepy Quest|unavailable|unavailable|[33](comparison/random/Creepy_Quest.txt)|unavailable|33|
|Skylanders Imaginators Game Helper|unavailable|[80](comparison/vitas/Skylanders_Imaginators_Game_Helper.txt)|[78](comparison/random/Skylanders_Imaginators_Game_Helper.txt)|[68](comparison/skillExplorer/Skylanders Imaginators Game Helper.zip)|174|
|RPG Dungeon Room Generator|unavailable|unavailable|[12](comparison/random/RPG_Dungeon_Room_Generator.txt)|[8](comparison/skillExplorer/RPG Dungeon Room Generator.zip)|15|
|Space Adventure|unavailable|[100](comparison/vitas/Space_Adventure.txt)|[44](comparison/random/Space_Adventure.txt)|[112](comparison/skillExplorer/Space Adventure.zip)|218|
|Russian Escape|unavailable|unavailable|[28](comparison/random/Russian_Escape.txt)|unavailable|28|
|Horrible Movie Plots|unavailable|unavailable|[37](comparison/random/Horrible_Movie_Plots.txt)|unavailable|37|
|Provinces of Spain|[71](comparison/user/Provinces_of_Spain.txt)|[59](comparison/vitas/Provinces_of_Spain.txt)|unavailable|unavailable|96|
|Listening Quiz|unavailable|unavailable|[7](comparison/random/Listening_Quiz.txt)|unavailable|7|
|OtakuGeneration|unavailable|unavailable|[5](comparison/random/OtakuGeneration.txt)|unavailable|5|
|A Musical Christmas|unavailable|unavailable|unavailable|unavailable|0|
|I Am A Triangle|[100](comparison/user/I_Am_A_Triangle.txt)|[96](comparison/vitas/I_Am_A_Triangle.txt)|[inconsistent behavior](comparison/random/I_Am_A_Triangle.txt)|unavailable|130|
|My Compliments|unavailable|[6](comparison/vitas/My_Compliments.txt)|[3](comparison/random/My_Compliments.txt)|[5](comparison/skillExplorer/My Compliments.zip)|12|
|Teams Quiz|unavailable|unavailable|unavailable|unavailable|0|
|Creative New Mexico Blog Reader|unavailable|[29](comparison/vitas/Creative_New_Mexico_Blog_Reader.txt)|[30](comparison/random/Creative_New_Mexico_Blog_Reader.txt)|[23](comparison/skillExplorer/Creative New Mexico Blog Reader.zip)|54|
|PrimeResi|[19](comparison/user/PrimeResi.txt)|[28](comparison/vitas/PrimeResi.txt)|[25](comparison/random/PrimeResi.txt)|unavailable|56|
|Parrot History|unavailable|unavailable|[23](comparison/random/Parrot_History.txt)|unavailable|23|
|The Crying Baby|unavailable|[34](comparison/vitas/The_Crying_Baby.txt)|[40](comparison/random/The_Crying_Baby.txt)|[38](comparison/skillExplorer/The Crying Baby.zip)|82|
|Virtual Trump|unavailable|unavailable|unavailable|unavailable|0|
|Fairy Milk|unavailable|unavailable|unavailable|unavailable|0|
|Quote Me|[55](comparison/user/Quote_Me.txt)|[inconsistent behavior](comparison/vitas/Quote_Me.txt)|[18](comparison/random/Quote_Me.txt)|[38](comparison/skillExplorer/Quote Me.zip)|107|
|Fundamental Valuation|[12](comparison/user/Fundamental_Valuation.txt)|[inconsistent behavior](comparison/vitas/Fundamental_Valuation.txt)|[inconsistent behavior](comparison/random/Fundamental_Valuation.txt)|[inconsistent behavior](comparison/skillExplorer/Fundamental Valuation.zip)|12|