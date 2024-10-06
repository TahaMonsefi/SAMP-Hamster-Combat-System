Hello, wherever you are in the world, you are definitely familiar with Telegram and its mini-games, one of which is Hamster Kabemet, and today I put this text draw (system) on the Github page. Thank you for following and supporting it to make it More projects the better

سلام شما در هر جایی این جهان باشید قطعا با تلگرام و مینی گیم های آن اشنایی دارید که یکی از انها همستر کابمت میباشد و امروز بنده این تکست دراو(سیستم) را در صفحه گیت هاب قرار دادم ممنون میشم فالو کنید و حمایت کنید جهت ساخت پروژه های بیشتر بهتر 

Здравствуйте, где бы вы ни находились в этом мире, вы наверняка знакомы с Telegram и его мини-играми, одна из которых — Hamster Kabemet, и сегодня я разместил этот текстовый рисунок (систему) на странице Github. Спасибо, что подписались и поддержали его. Чем больше проектов, тем лучше.

 Photo & Image:
 
![sa-mp-089](https://github.com/user-attachments/assets/c2b59d63-53bd-407a-857b-3bfe6dc3770d)




DOWNLOAD LINK:
[hamster.zip](https://github.com/user-attachments/files/17269614/hamster.zip)


```
`
//Variables
new PlayerText:PlayerTD[MAX_PLAYERS][30];


//Player Textdraws
PlayerTD[playerid][0] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][0], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][0], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][0], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][0], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][0], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][0], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][0], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][0], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][0], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][0], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][0], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][0], 0);

PlayerTD[playerid][1] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][1], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][1], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][1], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][1], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][1], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][1], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][1], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][1], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][1], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][1], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][1], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][1], 0);

PlayerTD[playerid][2] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][2], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][2], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][2], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][2], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][2], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][2], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][2], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][2], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][2], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][2], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][2], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][2], 0);

PlayerTD[playerid][3] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][3], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][3], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][3], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][3], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][3], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][3], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][3], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][3], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][3], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][3], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][3], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][3], 0);

PlayerTD[playerid][4] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][4], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][4], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][4], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][4], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][4], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][4], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][4], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][4], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][4], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][4], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][4], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][4], 0);

PlayerTD[playerid][5] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][5], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][5], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][5], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][5], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][5], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][5], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][5], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][5], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][5], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][5], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][5], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][5], 0);

PlayerTD[playerid][6] = CreatePlayerTextDraw(playerid, 549.000000, 199.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][6], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][6], 0.908333, 22.550003);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][6], 309.500000, 91.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][6], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][6], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][6], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][6], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][6], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][6], 135);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][6], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][6], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][6], 0);

PlayerTD[playerid][7] = CreatePlayerTextDraw(playerid, 515.000000, 203.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][7], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][7], 1.024999, 2.050002);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][7], 299.000000, 18.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][7], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][7], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][7], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][7], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][7], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][7], 1296911751);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][7], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][7], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][7], 0);

PlayerTD[playerid][8] = CreatePlayerTextDraw(playerid, 540.000000, 203.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][8], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][8], 1.024999, 2.050002);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][8], 299.000000, 18.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][8], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][8], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][8], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][8], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][8], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][8], 1296911751);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][8], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][8], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][8], 0);

PlayerTD[playerid][9] = CreatePlayerTextDraw(playerid, 564.000000, 203.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][9], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][9], 1.024999, 2.050002);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][9], 299.000000, 18.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][9], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][9], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][9], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][9], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][9], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][9], 1296911751);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][9], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][9], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][9], 0);

PlayerTD[playerid][10] = CreatePlayerTextDraw(playerid, 587.000000, 203.000000, "_");
PlayerTextDrawFont(playerid, PlayerTD[playerid][10], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][10], 1.024999, 2.050002);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][10], 299.000000, 18.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][10], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][10], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][10], 2);
PlayerTextDrawColor(playerid, PlayerTD[playerid][10], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][10], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][10], 1296911751);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][10], 1);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][10], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][10], 0);

PlayerTD[playerid][11] = CreatePlayerTextDraw(playerid, 538.000000, 248.000000, "1,000");
PlayerTextDrawFont(playerid, PlayerTD[playerid][11], 3);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][11], 0.300000, 0.800001);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][11], 398.000000, 12.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][11], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][11], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][11], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][11], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][11], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][11], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][11], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][11], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][11], 0);

PlayerTD[playerid][12] = CreatePlayerTextDraw(playerid, 516.000000, 244.000000, "ld_pool:ball");
PlayerTextDrawFont(playerid, PlayerTD[playerid][12], 4);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][12], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][12], 16.500000, 19.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][12], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][12], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][12], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][12], -2686721);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][12], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][12], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][12], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][12], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][12], 0);

PlayerTD[playerid][13] = CreatePlayerTextDraw(playerid, 493.000000, 266.000000, "AHOOOOO");
PlayerTextDrawFont(playerid, PlayerTD[playerid][13], 5);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][13], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][13], 105.500000, 99.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][13], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][13], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][13], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][13], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][13], 0);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][13], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][13], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][13], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][13], 0);
PlayerTextDrawSetPreviewModel(playerid, PlayerTD[playerid][13], 19315);
PlayerTextDrawSetPreviewRot(playerid, PlayerTD[playerid][13], -11.000000, 0.000000, -269.000000, 1.000000);
PlayerTextDrawSetPreviewVehCol(playerid, PlayerTD[playerid][13], 100, 1);

PlayerTD[playerid][14] = CreatePlayerTextDraw(playerid, 570.000000, 388.000000, "Boost");
PlayerTextDrawFont(playerid, PlayerTD[playerid][14], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][14], 0.237499, 0.850000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][14], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][14], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][14], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][14], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][14], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][14], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][14], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][14], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][14], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][14], 0);

PlayerTD[playerid][15] = CreatePlayerTextDraw(playerid, 504.000000, 390.000000, "1000/1000");
PlayerTextDrawFont(playerid, PlayerTD[playerid][15], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][15], 0.220833, 0.500000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][15], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][15], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][15], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][15], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][15], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][15], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][15], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][15], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][15], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][15], 0);

PlayerTD[playerid][16] = CreatePlayerTextDraw(playerid, 506.000000, 217.000000, "00:00");
PlayerTextDrawFont(playerid, PlayerTD[playerid][16], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][16], 0.158333, 0.449999);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][16], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][16], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][16], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][16], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][16], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][16], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][16], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][16], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][16], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][16], 0);

PlayerTD[playerid][17] = CreatePlayerTextDraw(playerid, 531.000000, 217.000000, "00:00");
PlayerTextDrawFont(playerid, PlayerTD[playerid][17], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][17], 0.158333, 0.449999);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][17], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][17], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][17], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][17], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][17], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][17], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][17], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][17], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][17], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][17], 0);

PlayerTD[playerid][18] = CreatePlayerTextDraw(playerid, 556.000000, 217.000000, "00:00");
PlayerTextDrawFont(playerid, PlayerTD[playerid][18], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][18], 0.158333, 0.449999);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][18], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][18], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][18], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][18], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][18], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][18], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][18], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][18], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][18], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][18], 0);

PlayerTD[playerid][19] = CreatePlayerTextDraw(playerid, 578.000000, 217.000000, "00:00");
PlayerTextDrawFont(playerid, PlayerTD[playerid][19], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][19], 0.158333, 0.449999);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][19], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][19], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][19], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][19], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][19], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][19], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][19], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][19], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][19], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][19], 0);

PlayerTD[playerid][20] = CreatePlayerTextDraw(playerid, 528.000000, 210.000000, "Daily reward");
PlayerTextDrawFont(playerid, PlayerTD[playerid][20], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][20], 0.125000, 0.550000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][20], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][20], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][20], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][20], 3);
PlayerTextDrawColor(playerid, PlayerTD[playerid][20], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][20], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][20], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][20], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][20], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][20], 0);

PlayerTD[playerid][21] = CreatePlayerTextDraw(playerid, 554.000000, 210.000000, "Daily chiper");
PlayerTextDrawFont(playerid, PlayerTD[playerid][21], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][21], 0.125000, 0.550000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][21], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][21], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][21], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][21], 3);
PlayerTextDrawColor(playerid, PlayerTD[playerid][21], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][21], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][21], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][21], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][21], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][21], 0);

PlayerTD[playerid][22] = CreatePlayerTextDraw(playerid, 577.000000, 210.000000, "Daily combo");
PlayerTextDrawFont(playerid, PlayerTD[playerid][22], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][22], 0.125000, 0.550000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][22], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][22], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][22], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][22], 3);
PlayerTextDrawColor(playerid, PlayerTD[playerid][22], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][22], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][22], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][22], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][22], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][22], 0);

PlayerTD[playerid][23] = CreatePlayerTextDraw(playerid, 602.000000, 210.000000, "Mini game");
PlayerTextDrawFont(playerid, PlayerTD[playerid][23], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][23], 0.125000, 0.550000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][23], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][23], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][23], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][23], 3);
PlayerTextDrawColor(playerid, PlayerTD[playerid][23], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][23], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][23], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][23], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][23], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][23], 0);

PlayerTD[playerid][24] = CreatePlayerTextDraw(playerid, 521.000000, 247.000000, "$");
PlayerTextDrawFont(playerid, PlayerTD[playerid][24], 1);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][24], 0.308333, 1.049999);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][24], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][24], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][24], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][24], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][24], 9109759);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][24], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][24], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][24], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][24], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][24], 0);

PlayerTD[playerid][25] = CreatePlayerTextDraw(playerid, 581.000000, 225.000000, "Hamster Kombat");
PlayerTextDrawFont(playerid, PlayerTD[playerid][25], 3);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][25], 0.254166, 1.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][25], 400.000000, 17.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][25], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][25], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][25], 3);
PlayerTextDrawColor(playerid, PlayerTD[playerid][25], 852308735);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][25], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][25], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][25], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][25], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][25], 0);

PlayerTD[playerid][26] = CreatePlayerTextDraw(playerid, 554.000000, 364.000000, "TEXTDRAW BY TAHAMONSEFI");
PlayerTextDrawFont(playerid, PlayerTD[playerid][26], 5);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][26], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][26], 38.500000, 40.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][26], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][26], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][26], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][26], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][26], 0);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][26], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][26], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][26], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][26], 0);
PlayerTextDrawSetPreviewModel(playerid, PlayerTD[playerid][26], 359);
PlayerTextDrawSetPreviewRot(playerid, PlayerTD[playerid][26], 2.000000, 20.000000, -181.000000, 2.339998);
PlayerTextDrawSetPreviewVehCol(playerid, PlayerTD[playerid][26], 1, 1);

PlayerTD[playerid][27] = CreatePlayerTextDraw(playerid, 582.000000, 224.000000, "ld_chat:thumbup");
PlayerTextDrawFont(playerid, PlayerTD[playerid][27], 4);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][27], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][27], 13.500000, 12.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][27], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][27], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][27], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][27], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][27], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][27], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][27], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][27], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][27], 0);

PlayerTD[playerid][28] = CreatePlayerTextDraw(playerid, 576.000000, 193.000000, "TMONSEFI.IR");
PlayerTextDrawFont(playerid, PlayerTD[playerid][28], 5);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][28], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][28], 19.500000, 23.000000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][28], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][28], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][28], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][28], -1);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][28], 0);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][28], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][28], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][28], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][28], 0);
PlayerTextDrawSetPreviewModel(playerid, PlayerTD[playerid][28], 2028);
PlayerTextDrawSetPreviewRot(playerid, PlayerTD[playerid][28], -89.000000, 0.000000, -179.000000, 1.000000);
PlayerTextDrawSetPreviewVehCol(playerid, PlayerTD[playerid][28], 1, 1);

PlayerTD[playerid][29] = CreatePlayerTextDraw(playerid, 499.000000, 242.000000, "ld_beat:cring");
PlayerTextDrawFont(playerid, PlayerTD[playerid][29], 4);
PlayerTextDrawLetterSize(playerid, PlayerTD[playerid][29], 0.600000, 2.000000);
PlayerTextDrawTextSize(playerid, PlayerTD[playerid][29], 96.500000, 122.500000);
PlayerTextDrawSetOutline(playerid, PlayerTD[playerid][29], 1);
PlayerTextDrawSetShadow(playerid, PlayerTD[playerid][29], 0);
PlayerTextDrawAlignment(playerid, PlayerTD[playerid][29], 1);
PlayerTextDrawColor(playerid, PlayerTD[playerid][29], 16777215);
PlayerTextDrawBackgroundColor(playerid, PlayerTD[playerid][29], 255);
PlayerTextDrawBoxColor(playerid, PlayerTD[playerid][29], 50);
PlayerTextDrawUseBox(playerid, PlayerTD[playerid][29], 0);
PlayerTextDrawSetProportional(playerid, PlayerTD[playerid][29], 1);
PlayerTextDrawSetSelectable(playerid, PlayerTD[playerid][29], 0);`

```
