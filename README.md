# Graduation Project => VsionX 

### Team memmber 
1. Abd-Elwahaab Hany     Id:4210312  CV Enginner
2. Mohamed Abd-Elhalem   Id:4210161  Data Analtsis
3. Ahmed Sami            Id:4210332  CV Enginner
4. Sameh Mohamed         Id:4210305  backend Enginner
5. Mohamed Ahmed         Id:4210446  Mobile  Developer
6. Yousef Fawzy          Id:4210166  Data Analtsis
7. gala salah            Id:4210058  backend Enginner
8. Ahmed Salah           Id:4210253  Mobile Developer
## Standardization for Project Selection

### Criteria:

1. **Problem Definition**
   - Can we clearly define the problem?

2. **Market Segmentation**
   - Who is the target audience?
   - What are the key characteristics of this segment?

4. **Data Availability**
   - Is suitable data available on platforms like Kaggle?
   - Is web scraping a viable option for data collection?
   - Are there any ethical or legal concerns with data acquisition?

5. **Market Demand**
   - Is there evidence of market interest or need?
   - Are there potential stakeholders or users for this project?
  
### First Idea: showing the talanet local player to help the dicion makers 

1. **problem**
   there are many football players in egypt every year in ramadan shareing thir skkils of playing at the internet, so need to build a social media 
   pulic platform for this video's when create an acount we need to know if one player or teem ?
   1. if one player we will prepare his profile with 0 skills as defualt values then with publishing we will detect him by in the first we will ask 
      from him some of skills without 
   
3. **Market Segmentation**
   -Targeting heavy transport owners or those who travel distances longer than 1 hours.
   
4. **Data Availability**
   -There is a wealth of public data available on platforms like YouTube.
   
5. **Market Demand**
   -Bein Sport, market place for transfare market depend on player analtsis 

arabic-description : 
فكرة المشروع علشان محدش يقول اي كلام و تبقي مرجع لينا
بنفكر نعمل app الشباب الي بيتلعب في دوري درجه تالته أو الشباب الي بيتلعب في مراكز شباب أو الشباب الي بيتلعب حجوزات كورة و برضوا كل شهر رمضان بيبقي في دورة رمضانية بين فرق في المناطق الشعبيه عاوز بقي الناس دي تستخدم التطبيق بيتعنا و نيداء بإستخدام computer vision model نحلل لعب الشباب دي بحيث أن دلوقتي بقي اغلب الانتقالات بيتاعت اللعيبه المحترفه الكشافة أو المسؤولين بيشوفوا تحليلاتهم و بالتالي يساعدهم علي اتخاذ القرار و اكتشاف المواهب و دا أن شاء الله يلاقي تفاعل كبير عند الشباب لأن في شباب كتير حاسة أنها بيتلعب حلو بس معندهمش فرصه طب ايه ال journey الي هتقابل المستخدم احنا عندنا اتنين مستخدمين أما اللعيبه أو المسؤولين بيتوع الأندية و في ناس عادية كبيرة في السن بس بيتحب تتفرج ف دول هنقول أنهم تبع المسؤولين 
المهم اي حد يقدر يفتح ال app  و يشوف list كبيرة من الفيديوهات اول أما الفديو يشتغل ب خمس ثواني هنعرض كرت اللاعب زي بيس كدا و بعد كدا نشغل الفديو الي ممكن  يكون اكتر من دقيقه و في نفس الوقت في shorts للفديوهات الدقيقه فيما أقل و من وقت ل التاني في عروض علي دورات رمضانية او غيرة في بثوث و برضوا في شاشة للبثوث بس شرط يبقي بث ل دورة طب بعد كدا كل شاب هيبقي ليه profile  بيعرض تحليلات عنه و فديوهات و لو هو تبع فريق الفريق دا حقق انجازات ايه و هكذا و من هنا نقدر نقول إن شاب يقدر يعمل فريق و دا القائد و يبعت دعوه ل زميلة و ينضموا للفريق دا و يقدر ينشئ دورة و يبعت دعوة للفرق التانيه لو تحب تنضم المهم الفريق مش هيبقي فريق إلا بعد ماشركة عدد معين و الدوري مش دوري إلا بعد مشاركة عدد معين 
كدا قولنا الشاشه الرئيسيه و قولنا شاشة ال profile  في شاشه كمان للمركاتوا و كل شاب هيبقي ليه سعر عندنا علي ال app و يقدر يشوف زميلة و هكذا و محتاجين شاشة للمحادثة و لل notification و شاشة للأعدادات زي بيتاعت الفرق و الدورات الأسم الصورة و الحجات الي شبة كدا

english-description : 
We are developing a mobile app that allows users to upload and share videos of football players, captured during informal matches, training sessions, or tournaments (e.g., school courses, academies, Ramadan tournaments, or college events). These videos will be analyzed using performance metrics like pass accuracy, shot accuracy, and other key skills. Players can optionally complete specific tasks or challenges, which help enhance the analysis of their performance.
The analyzed data will then be used to assign points to players, which they can redeem or sell through our marketplace to clubs or academies interested in scouting new talent. The app will have a social media-like interface, similar to TikTok, where users can view, interact with, and share player videos.


1. Object Detection and Tracking

    Use object detection models (e.g., YOLO, Faster R-CNN) to detect players, the ball, and referees.
    For tracking player movement, use techniques like SORT, DeepSORT, or ByteTrack, which can associate detected players frame-by-frame and provide consistent ID tracking.

2. Pose Estimation

    Implement pose estimation models (e.g., OpenPose or MoveNet) to identify body landmarks for actions such as dribbling, passing, or shooting.
    This data can also be useful to evaluate balance, movement efficiency, and agility.

3. Activity Recognition

    Using pose and movement data, apply activity recognition models to classify specific actions (e.g., kicking, sprinting, defending).
    Models like Temporal Convolutional Networks (TCN) or 3D CNNs can analyze sequences to understand tactical actions.

4. Performance Metrics Extraction

    Speed and distance: Calculate using tracked coordinates to measure sprinting, acceleration, and stamina.
    Ball control and passing accuracy: Use the ball’s coordinates and trajectory analysis to estimate control duration and successful passes.

5. Team Dynamics and Positioning Analysis

    Spatial patterns: By analyzing the players’ relative positions, assess formations, off-the-ball movements, and spacing.
    Use clustering or density-based methods to understand positioning tendencies during various phases (attack, defense).
1. Player-Specific Metrics

    Speed and Acceleration: Track players’ speeds and acceleration patterns to assess their agility, reaction time, and physical fitness.
    Positional Data: Map players’ positions over time to evaluate movement patterns, off-the-ball positioning, and marking tendencies.
    Ball Control Time: Measure how long each player controls the ball, an indicator of dribbling skills and playmaking potential.
    Shot and Pass Accuracy: Track shot and pass attempts, measuring accuracy based on the intended target. This can help identify technical skills and decision-making.

2. Skill-Based Metrics

    Pass Success Rate: Calculate the percentage of successful passes, which can indicate passing accuracy and decision-making.
    Dribbling Success Rate: Measure successful dribbling attempts, showing a player’s ability to maneuver under pressure.
    Goal and Assist Contribution: Identify goals scored and assists made, directly reflecting offensive contributions.

3. Physical & Tactical Metrics

    Heatmaps of Movement: Visualize areas where players spend most of their time, useful for understanding roles, such as a defender’s area or a striker’s attacking zones.
    Offensive vs. Defensive Actions: Track tackles, interceptions, and other defensive actions, distinguishing between defensive and offensive tendencies.
    Stamina & Fatigue Indicators: Analyzing changes in speed and movement over time can help indicate stamina and potential fatigue patterns.

4. Team Dynamics and Tactical Patterns

    Formation Consistency: Analyze spatial data to see if players maintain their formation, switch roles, or drift out of position.
    Pressing Intensity: Measure the frequency and success rate of pressing the opponent when they have possession.
    Player Interactions and Passing Networks: Visualize passing networks to understand connections between players and identify key playmakers.

5. Behavioral Metrics

    Decision-Making Speed: Track the time taken for decisions, like passing or shooting after receiving the ball, to gauge a player's reaction and anticipation.
    Game Awareness: Indicators like tracking how often a player shifts their position in response to ball movement, teammates, or opponents.

This data will enable scouts and coaches to assess not only technical skills but also game intelligence, fitness, and tactical adaptability. Each metric provides actionable insights for improving individual and team performance.
