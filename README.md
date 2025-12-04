<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>المراجعة النهائية - التمريض النسائي والتوليد</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #9b59b6;
            --light-color: #ecf0f1;
            --success-color: #27ae60;
            --warning-color: #e74c3c;
        }
        
        body {
            font-family: 'Cairo', sans-serif;
            line-height: 1.8;
            color: #333;
            background-color: #f8f9fa;
        }
        
        .english-text {
            font-family: 'Roboto', sans-serif;
            color: var(--primary-color);
            font-weight: 500;
            border-right: 3px solid var(--secondary-color);
            padding-right: 15px;
            margin-bottom: 10px;
        }
        
        .arabic-text {
            color: #2d3436;
            font-weight: 600;
            padding-right: 15px;
            margin-bottom: 25px;
            border-bottom: 1px dashed #ddd;
            padding-bottom: 10px;
        }
        
        .section-header {
            background: linear-gradient(to right, var(--primary-color), var(--accent-color));
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin: 30px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .card {
            border: none;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            margin-bottom: 25px;
            transition: transform 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .card-header {
            background-color: var(--light-color);
            border-bottom: 3px solid var(--secondary-color);
            font-weight: 700;
            font-size: 1.2rem;
            border-radius: 15px 15px 0 0 !important;
        }
        
        .image-container {
            text-align: center;
            margin: 25px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            background-color: white;
            padding: 15px;
            border: 1px solid #e9ecef;
        }
        
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s;
        }
        
        .image-container img:hover {
            transform: scale(1.02);
        }
        
        .image-caption {
            font-style: italic;
            color: #7f8c8d;
            margin-top: 10px;
            font-size: 0.9rem;
            padding: 5px;
            background-color: #f8f9fa;
            border-radius: 5px;
        }
        
        .highlight-box {
            background-color: #e8f4fc;
            border-right: 5px solid var(--secondary-color);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .procedure-step {
            background-color: #f9f9f9;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border-right: 5px solid var(--success-color);
        }
        
        .note-box {
            background-color: #fffde7;
            border: 2px dashed #f1c40f;
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .equipment-list {
            list-style-type: none;
            padding-right: 0;
        }
        
        .equipment-list li {
            padding: 8px 0;
            border-bottom: 1px solid #eee;
        }
        
        .equipment-list li:before {
            content: "✓";
            color: var(--success-color);
            font-weight: bold;
            margin-left: 10px;
        }
        
        .instrument-image {
            width: 100%;
            max-width: 200px;
            height: 150px;
            object-fit: contain;
            margin: 10px auto;
            display: block;
            border-radius: 8px;
            background-color: #f8f9fa;
            padding: 10px;
        }
        
        footer {
            background-color: var(--primary-color);
            color: white;
            padding: 30px 0;
            margin-top: 50px;
        }
        
        .nav-tabs .nav-link {
            color: var(--primary-color);
            font-weight: 600;
        }
        
        .nav-tabs .nav-link.active {
            background-color: var(--secondary-color);
            color: white;
            border-color: var(--secondary-color);
        }
        
        @media print {
            .no-print {
                display: none;
            }
            
            .section-header {
                background: #2c3e50 !important;
                -webkit-print-color-adjust: exact;
                color: white !important;
            }
            
            .image-container {
                break-inside: avoid;
            }
        }
        
        .sticky-sidebar {
            position: sticky;
            top: 20px;
        }
    </style>
</head>
<body>
    <!-- شريط التنقل -->
    <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: var(--primary-color);">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-stethoscope me-2"></i>المراجعة النهائية - التمريض النسائي والتوليد
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#perineal-care">العناية بالعجان</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#abdominal-exam">الفحص البطني</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#vaginal-exam">الفحص المهبلي</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#delivery">مرحلة المخاض</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- المحتوى الرئيسي -->
    <div class="container mt-5">
        <!-- العنوان الرئيسي -->
        <div class="text-center mb-5">
            <h1 class="display-4 fw-bold" style="color: var(--primary-color);">
                <i class="fas fa-book-medical me-2"></i>المراجعة النهائية للتمريض النسائي والتوليد
            </h1>
            <p class="lead" style="color: var(--accent-color);">
                جمع وتنظيم للمحتوى التعليمي مع الترجمة العربية والصور التوضيحية
            </p>
            <div class="row mt-4">
                <div class="col-md-3 col-6 mb-3">
                    <div class="card text-center py-3">
                        <i class="fas fa-hand-holding-medical fa-3x mb-3" style="color: var(--secondary-color);"></i>
                        <h5>العناية بالعجان</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6 mb-3">
                    <div class="card text-center py-3">
                        <i class="fas fa-procedures fa-3x mb-3" style="color: var(--accent-color);"></i>
                        <h5>الفحص البطني</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6 mb-3">
                    <div class="card text-center py-3">
                        <i class="fas fa-female fa-3x mb-3" style="color: var(--success-color);"></i>
                        <h5>الفحص المهبلي</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6 mb-3">
                    <div class="card text-center py-3">
                        <i class="fas fa-baby fa-3x mb-3" style="color: var(--warning-color);"></i>
                        <h5>مرحلة المخاض</h5>
                    </div>
                </div>
            </div>
        </div>

        <!-- قسم العناية بالعجان -->
        <div id="perineal-care" class="section-header">
            <h2><i class="fas fa-hand-holding-medical me-2"></i>العناية بمنطقة العجان (Perineal Care)</h2>
        </div>

        <div class="row">
            <div class="col-lg-8">
                <div class="card">
                    <div class="card-header">تعريف العناية بالعجان</div>
                    <div class="card-body">
                        <div class="english-text">Perineal care is an external irrigation, cleansing and/or swabbing of the vulva and perineum.</div>
                        <div class="arabic-text">العناية بمنطقة العجان هي عملية ري خارجي، وتنظيف و/أو مسح للفرج والعجان.</div>
                        
                        <div class="image-container">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Female_perineum_%28with_labels%29.png/500px-Female_perineum_%28with_labels%29.png" alt="تشريح منطقة العجان">
                            <div class="image-caption">التشريح الدقيق لمنطقة العجان الأنثوي مع تحديد المكونات الرئيسية</div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">أهداف العناية بالعجان</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1551601651-2a8555f1a136?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="منع العدوى">
                                    <div class="image-caption">التنظيف السليم يمنع انتشار العدوى</div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <ol>
                                    <li>
                                        <div class="english-text">To clean the vulva and perineum</div>
                                        <div class="arabic-text">تنظيف الفرج والعجان</div>
                                    </li>
                                    <li>
                                        <div class="english-text">Prevent and control the spread of infection</div>
                                        <div class="arabic-text">الوقاية من انتشار العدوى والتحكم بها</div>
                                    </li>
                                    <li>
                                        <div class="english-text">Prevent skin breakdown</div>
                                        <div class="arabic-text">منع تقرحات الجلد</div>
                                    </li>
                                    <li>
                                        <div class="english-text">Reduce unpleasant odors</div>
                                        <div class="arabic-text">تقليل الروائح الكريهة</div>
                                    </li>
                                    <li>
                                        <div class="english-text">Prevent skin irritation</div>
                                        <div class="arabic-text">منع تهيج الجلد</div>
                                    </li>
                                </ol>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">الخطوات الإجرائية للعناية بالعجان</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="procedure-step">
                                    <div class="english-text">Introduce yourself and explain procedure to woman. Keep the privacy.</div>
                                    <div class="arabic-text">تعريف النفس وشرح الإجراء للمرأة. الحفاظ على الخصوصية.</div>
                                </div>
                                <div class="procedure-step">
                                    <div class="english-text">Provide the woman with the opportunity to empty her bladder.</div>
                                    <div class="arabic-text">توفير الفرصة للمرأة لإفراغ المثانة.</div>
                                </div>
                                <div class="procedure-step">
                                    <div class="english-text">Wash hands and wear gloves.</div>
                                    <div class="arabic-text">غسل اليدين وارتداء القفازات.</div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1586773860418-dc22f8b874bc?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="تقنيات التعقيم">
                                    <div class="image-caption">تقنيات التعقيم وارتداء القفازات بشكل صحيح</div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Female_anatomy_-_cleansing_direction.svg/600px-Female_anatomy_-_cleansing_direction.svg.png" alt="اتجاهات تنظيف منطقة العجان">
                            <div class="image-caption">الاتجاه الصحيح للتنظيف (من الأمام إلى الخلف) لمنع انتقال العدوى</div>
                        </div>
                        
                        <div class="row mt-4">
                            <div class="col-md-8">
                                <div class="procedure-step">
                                    <div class="english-text">Assist woman in assuming dorsal recumbent position.</div>
                                    <div class="arabic-text">مساعدة المرأة في اتخاذ وضعية الاستلقاء الظهري.</div>
                                </div>
                                <div class="procedure-step">
                                    <div class="english-text">Assess the woman's genital area for color, odor, lesions, masses, swelling, irritation, tenderness, and discharge.</div>
                                    <div class="arabic-text">تقييم منطقة الأعضاء التناسلية للمرأة من حيث اللون، الرائحة، الآفات، الكتل، التورم، التهيج، الألم، والإفرازات.</div>
                                </div>
                            </div>
                            <div class="col-md-4">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="وضعية المريضة">
                                    <div class="image-caption">الوضعية الصحيحة للمريضة أثناء الإجراء</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="col-lg-4">
                <div class="sticky-sidebar">
                    <div class="card">
                        <div class="card-header">الأدوات والمعدات المطلوبة</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://images.unsplash.com/photo-1584302179602-e76e20c3e0e5?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="أدوات العناية بالعجان">
                                <div class="image-caption">مجموعة أدوات العناية بالعجان الأساسية</div>
                            </div>
                            
                            <ul class="equipment-list">
                                <li>
                                    <div class="english-text">Bath blanket or sheet</div>
                                    <div class="arabic-text">بطانية أو ملاءة</div>
                                </li>
                                <li>
                                    <div class="english-text">Wash basin</div>
                                    <div class="arabic-text">حوض غسيل</div>
                                </li>
                                <li>
                                    <div class="english-text">Soapy water or antiseptic solution</div>
                                    <div class="arabic-text">ماء صابون أو محلول مطهر</div>
                                </li>
                                <li>
                                    <div class="english-text">Towels and wash clothes</div>
                                    <div class="arabic-text">مناشف وملابس للغسيل</div>
                                </li>
                                <li>
                                    <div class="english-text">Cotton balls and tissue forceps</div>
                                    <div class="arabic-text">كرات قطنية وملقط الأنسجة</div>
                                </li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="note-box">
                        <h5><i class="fas fa-lightbulb me-2"></i>ملاحظة هامة:</h5>
                        <p>يجب التنظيف دائمًا <strong>من الأمام إلى الخلف</strong> (من منطقة الفرج نحو فتحة الشرج) لمنع انتقال البكتيريا من منطقة الشرج إلى المهبل والإحليل، مما يقلل من خطر التهاب المسالك البولية والتهابات المهبل.</p>
                        <div class="image-container mt-3">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/Clean_from_front_to_back.png/400px-Clean_from_front_to_back.png" alt="التنظيف من الأمام إلى الخلف">
                            <div class="image-caption">مبدأ التنظيف من الأمام إلى الخلف للوقاية من العدوى</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- قسم الفحص البطني -->
        <div id="abdominal-exam" class="section-header">
            <h2><i class="fas fa-procedures me-2"></i>الفحص البطني أثناء الحمل (Abdominal Examination)</h2>
        </div>

        <div class="row">
            <div class="col-lg-8">
                <div class="card">
                    <div class="card-header">أهداف الفحص البطني أثناء الحمل</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="english-text">The examination aims to estimate the period of gestation, determine presentation, lie, position, attitude and engagement of the presenting part, and assess fetal well-being.</div>
                                <div class="arabic-text">يهدف الفحص إلى تقدير مدة الحمل، تحديد وضعية الجنين، علاقته بالمحور الطولي للرحم، اتجاهه، وضعه، ونزول الجزء المقدم، وتقييم صحة الجنين.</div>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1576091160399-112ba8d25d1f?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="فحص الحامل">
                                    <div class="image-caption">الفحص البطني الدقيق للحامل</div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Fetal_positions.svg/600px-Fetal_positions.svg.png" alt="وضعيات الجنين المختلفة">
                            <div class="image-caption">وضعيات الجنين المختلفة داخل الرحم وتحديد وضعية الرأس</div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">المناورات الأربعة للفحص البطني (Leopold's Maneuvers)</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6 mb-3">
                                <div class="highlight-box">
                                    <h5>المناورة الأولى</h5>
                                    <div class="english-text">Fundal grip or 1st maneuver</div>
                                    <div class="arabic-text">القبضة القاعية أو المناورة الأولى</div>
                                    <p class="mt-2">تحديد أي قطب للجنين موجود في قاع الرحم (رأس أم مؤخرة).</p>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Leopold_maneuver_1.png/300px-Leopold_maneuver_1.png" alt="المناورة الأولى">
                                        <div class="image-caption">المناورة الأولى: تحديد قاع الرحم</div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 mb-3">
                                <div class="highlight-box">
                                    <h5>المناورة الثانية</h5>
                                    <div class="english-text">Lateral or umbilical grip (2nd maneuver)</div>
                                    <div class="arabic-text">القبضة الجانبية أو قبضة السرة (المناورة الثانية)</div>
                                    <p class="mt-2">تحديد موقع ظهر الجنين وأطرافه.</p>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Leopold_maneuver_2.png/300px-Leopold_maneuver_2.png" alt="المناورة الثانية">
                                        <div class="image-caption">المناورة الثانية: تحديد موقع الظهر</div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 mb-3">
                                <div class="highlight-box">
                                    <h5>المناورة الثالثة</h5>
                                    <div class="english-text">Pawlik grip or 1st pelvic grip (3rd maneuver)</div>
                                    <div class="arabic-text">قبضة بأوليك أو القبضة الحوضية الأولى (المناورة الثالثة)</div>
                                    <p class="mt-2">تحديد الجزء المقدم ومدى تحرره.</p>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Leopold_maneuver_3.png/300px-Leopold_maneuver_3.png" alt="المناورة الثالثة">
                                        <div class="image-caption">المناورة الثالثة: تحديد الجزء المقدم</div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 mb-3">
                                <div class="highlight-box">
                                    <h5>المناورة الرابعة</h5>
                                    <div class="english-text">2nd pelvic grip or deep pelvic palpation (4th maneuver)</div>
                                    <div class="arabic-text">القبضة الحوضية الثانية أو الفحص الحوضي العميق (المناورة الرابعة)</div>
                                    <p class="mt-2">تحديد مستوى نزول الجزء المقدم.</p>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Leopold_maneuver_4.png/300px-Leopold_maneuver_4.png" alt="المناورة الرابعة">
                                        <div class="image-caption">المناورة الرابعة: تحديد مستوى النزول</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">سماع دقات قلب الجنين</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="english-text">Fetal Heart Rate Evaluation: Normal range is 120-160 beats per minute</div>
                                <div class="arabic-text">تقييم نبضات قلب الجنين: المدى الطبيعي هو 120-160 نبضة في الدقيقة</div>
                                <ul class="mt-3">
                                    <li>النبض الطبيعي: 120-160 نبضة/دقيقة</li>
                                    <li>تسرع القلب الجنيني: أكثر من 160 نبضة/دقيقة</li>
                                    <li>بطء القلب الجنيني: أقل من 120 نبضة/دقيقة</li>
                                </ul>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1559757175-0eb30cd8c063?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="سماع قلب الجنين">
                                    <div class="image-caption">استخدام جهاز الدوبلر لسماع نبضات قلب الجنين</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="col-lg-4">
                <div class="sticky-sidebar">
                    <div class="card">
                        <div class="card-header">الأدوات المطلوبة للفحص البطني</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://images.unsplash.com/photo-1551601651-2a8555f1a136?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="أدوات الفحص البطني">
                                <div class="image-caption">مجموعة أدوات الفحص البطني الأساسية</div>
                            </div>
                            
                            <ul class="equipment-list">
                                <li>
                                    <div class="english-text">Tape measure</div>
                                    <div class="arabic-text">شريط قياس</div>
                                </li>
                                <li>
                                    <div class="english-text">Pinard fetoscope or sonic fetal heart sound device</div>
                                    <div class="arabic-text">سماعة ليوبولد الجنينية أو جهاز صوتي لسماع نبضات قلب الجنين</div>
                                </li>
                                <li>
                                    <div class="english-text">Client record</div>
                                    <div class="arabic-text">سجل المريضة</div>
                                </li>
                                <li>
                                    <div class="english-text">Stethoscope</div>
                                    <div class="arabic-text">سماعة طبية</div>
                                </li>
                                <li>
                                    <div class="english-text">Gloves</div>
                                    <div class="arabic-text">قفازات</div>
                                </li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="card mt-4">
                        <div class="card-header">تحضير المريضة للفحص</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="تحضير المريضة">
                                <div class="image-caption">الوضعية الصحيحة للمريضة أثناء الفحص البطني</div>
                            </div>
                            
                            <ol class="mt-3">
                                <li>التعريف بالنفس وشرح الإجراء للأم</li>
                                <li>أخذ موافقة الأم على إجراء الفحص</li>
                                <li>الحفاظ على الخصوصية</li>
                                <li>غسل اليدين وارتداء القفازات</li>
                                <li>طلب إفراغ المثانة قبل الفحص</li>
                                <li>مساعدة المرأة على الاستلقاء على ظهرها مع ثني الركبتين قليلاً</li>
                                <li>كشف البطن من العانة حتى القص</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- قسم الفحص المهبلي -->
        <div id="vaginal-exam" class="section-header">
            <h2><i class="fas fa-female me-2"></i>الفحص المهبلي (Vaginal Examination)</h2>
        </div>

        <div class="row">
            <div class="col-lg-8">
                <div class="card">
                    <div class="card-header">تعريف وأهمية الفحص المهبلي</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-7">
                                <div class="english-text">Vaginal examination is a clinical procedure performed by a nurse or physician. It is considered a "blind examination" because it relies on touch rather than visual inspection.</div>
                                <div class="arabic-text">الفحص المهبلي هو إجراء سريري يجريه الطبيب أو الممرضة. ويعتبر فحصًا "أعمى" لأنه يعتمد على اللمس وليس الرؤية المباشرة.</div>
                                
                                <div class="note-box mt-3">
                                    <h6><i class="fas fa-info-circle"></i> معلومات هامة:</h6>
                                    <p>في الفحص المهبلي، يكون المهبل <strong>الدافئ والرطب</strong> طبيعيًا، بينما يشير <strong>الساخن والجاف</strong> إلى الجفاف أو العدوى أو انسداد المخاض.</p>
                                </div>
                            </div>
                            <div class="col-md-5">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1584467735871-8db9ac8d0916?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="فحص مهبلي">
                                    <div class="image-caption">إجراء الفحص المهبلي بشكل احترافي</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">تغيرات عنق الرحم أثناء المخاض</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="highlight-box">
                                    <h5>انمحاء عنق الرحم</h5>
                                    <div class="english-text">Effacement: shortening and thinning of cervix (2 cm → paper-thin)</div>
                                    <div class="arabic-text">الانمحاء: قصر وترقيق عنق الرحم (من 2 سم إلى رقيق كالورقة)</div>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Cervical_effacement_diagram.svg/300px-Cervical_effacement_diagram.svg.png" alt="انمحاء عنق الرحم">
                                        <div class="image-caption">مراحل انمحاء عنق الرحم تدريجيًا</div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="highlight-box">
                                    <h5>اتساع عنق الرحم</h5>
                                    <div class="english-text">Dilatation: widening of cervix (0 → 10 cm)</div>
                                    <div class="arabic-text">الاتساع: توسع عنق الرحم من مغلق إلى 10 سم</div>
                                    <div class="image-container mt-2">
                                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Cervical_dilation_diagram.svg/300px-Cervical_dilation_diagram.svg.png" alt="اتساع عنق الرحم">
                                        <div class="image-caption">مراحل اتساع عنق الرحم من 0 إلى 10 سم</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container mt-4">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Cervical_effacement.svg/600px-Cervical_effacement.svg.png" alt="مراحل انمحاء واتساع عنق الرحم">
                            <div class="image-caption">المراحل المتكاملة لانمحاء واتساع عنق الرحم أثناء المخاض</div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">مستوى الجنين (Fetal Station)</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="english-text">Station: relation of presenting part to ischial spines (-3 to +3)</div>
                                <div class="arabic-text">المستوى: علاقة الجزء المقدم بالأشواك الإسكية (من -3 إلى +3)</div>
                                
                                <div class="mt-4">
                                    <h6>تفسير المستويات:</h6>
                                    <ul>
                                        <li><strong>المستوى -3:</strong> الرأس يطفو فوق الحوض</li>
                                        <li><strong>المستوى -2:</strong> الرأس فوق الأشواك الإسكية</li>
                                        <li><strong>المستوى -1:</strong> الرأس عند مستوى الأشواك الإسكية</li>
                                        <li><strong>المستوى 0:</strong> الرأس عند مستوى الأشواك الإسكية</li>
                                        <li><strong>المستوى +1:</strong> الرأس تحت الأشواك الإسكية</li>
                                        <li><strong>المستوى +2:</strong> الرأس منخفض في الحوض</li>
                                        <li><strong>المستوى +3:</strong> الرأس يظهر في فتحة المهبل</li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Fetal_Station.svg/500px-Fetal_Station.svg.png" alt="مستوى نزول الجنين">
                                    <div class="image-caption">مستوى نزول الجنين بالنسبة للأشواك الإسكية</div>
                                </div>
                                
                                <div class="image-container mt-3">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Fetal_head_at_-1_station.svg/400px-Fetal_head_at_-1_station.svg.png" alt="رأس الجنين عند مستوى -1">
                                    <div class="image-caption">رأس الجنين عند المستوى -1 فوق الأشواك الإسكية</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="col-lg-4">
                <div class="sticky-sidebar">
                    <div class="card">
                        <div class="card-header">الأدوات المطلوبة للفحص المهبلي</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://images.unsplash.com/photo-1586773860418-dc22f8b874bc?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="أدوات الفحص المهبلي">
                                <div class="image-caption">مجموعة أدوات الفحص المهبلي الأساسية</div>
                            </div>
                            
                            <ul class="equipment-list">
                                <li>
                                    <div class="english-text">Sterile or disposable gloves</div>
                                    <div class="arabic-text">قفازات معقمة أو للاستعمال مرة واحدة</div>
                                </li>
                                <li>
                                    <div class="english-text">Lubricant (K.Y gel)</div>
                                    <div class="arabic-text">مزلق (جل كي واي)</div>
                                </li>
                                <li>
                                    <div class="english-text">Antiseptic solution</div>
                                    <div class="arabic-text">محلول مطهر</div>
                                </li>
                                <li>
                                    <div class="english-text">Sterile pad</div>
                                    <div class="arabic-text">فوطة معقمة</div>
                                </li>
                                <li>
                                    <div class="english-text">Vaginal speculum</div>
                                    <div class="arabic-text">منظار مهبلي</div>
                                </li>
                                <li>
                                    <div class="english-text">Good light source</div>
                                    <div class="arabic-text">مصدر إضاءة جيد</div>
                                </li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="card mt-4">
                        <div class="card-header">وضعيات الفحص المهبلي</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Lithotomy_position.png/400px-Lithotomy_position.png" alt="وضعية ليثوتومي">
                                <div class="image-caption">وضعية ليثوتومي (الوالدة) للفحص المهبلي</div>
                            </div>
                            
                            <h6 class="mt-3">الوضعيات الشائعة:</h6>
                            <ol>
                                <li>وضعية ليثوتومي (الأكثر شيوعًا)</li>
                                <li>وضعية الاستلقاء الجانبي</li>
                                <li>وضعية القرفصاء</li>
                                <li>وضعية الركوع</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- قسم المرحلة الثانية للمخاض -->
        <div id="delivery" class="section-header">
            <h2><i class="fas fa-baby me-2"></i>التعامل مع المرحلة الثانية من المخاض</h2>
            <p class="mb-0">Handling during second stage of labor</p>
        </div>

        <div class="row">
            <div class="col-lg-8">
                <div class="card">
                    <div class="card-header">أدوات عربة الولادة (Delivery Trolley)</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1584467735871-8db9ac8d0916?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="عربة الولادة">
                                    <div class="image-caption">عربة الولادة المجهزة بشكل كامل</div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <h5>المحتويات الأساسية:</h5>
                                <ul>
                                    <li>منظار مهبلي (Speculum)</li>
                                    <li>ملقط شرياني (Artery Forceps)</li>
                                    <li>حامل الإبرة (Needle holder)</li>
                                    <li>حامل الإسفنج (Sponge holder)</li>
                                    <li>ملقط الإبهام (Thumb Forceps)</li>
                                    <li>مقص مستقيم ومقوس (Scissors)</li>
                                    <li>رباط الحبل السري (Cord Tie)</li>
                                    <li>قفازات مقاس 6، 6.5</li>
                                    <li>خيوط كاتجوت (Catgut)</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">ركن العناية بالمولود الجديد</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-7">
                                <div class="english-text">NEWBORN CARE CORNER: Essential equipment for newborn resuscitation and care</div>
                                <div class="arabic-text">ركن العناية بالمولود الجديد: معدات أساسية لإنعاش المولود والعناية به</div>
                                
                                <ul class="mt-3">
                                    <li>سخان إشعاعي (Radiant warmer)</li>
                                    <li>جهاز تنفس يدوي لحديثي الولادة (Neonatal Ambu Bag)</li>
                                    <li>مزيل المخاط (Mucous Extractor)</li>
                                    <li>صينية رضيع مع قماش نظيف</li>
                                    <li>أسطوانة أكسجين مع عداد التدفق</li>
                                    <li>قسطرة أنفية (Nasal catheter)</li>
                                    <li>منظار حنجرة وأنبوب تنبيب رغامي</li>
                                    <li>سماعة أطفال (Paediatric Stethoscope)</li>
                                    <li>ميزان أطفال (Baby scale)</li>
                                </ul>
                            </div>
                            <div class="col-md-5">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1519483067481-199e2b9c6b26?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="ركن المولود">
                                    <div class="image-caption">ركن العناية بالمولود الجديد مجهز بالكامل</div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container mt-4">
                            <img src="https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="معدات إنعاش المولود">
                            <div class="image-caption">معدات إنعاش المولود الجديد الأساسية</div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">مجموعة بضع الفرج والعمليات الصغرى</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <table class="table table-bordered">
                                    <thead>
                                        <tr>
                                            <th>الوصف</th>
                                            <th>الكمية</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr><td>مقص بضع الفرج</td><td>1</td></tr>
                                        <tr><td>مقص مستقيم</td><td>1</td></tr>
                                        <tr><td>ملقط حامل الإسفنج</td><td>1</td></tr>
                                        <tr><td>منظار مهبلي</td><td>1</td></tr>
                                        <tr><td>ملقط شرياني مستقيم</td><td>2</td></tr>
                                        <tr><td>ملقط شرياني مقوس</td><td>2</td></tr>
                                        <tr><td>حامل الإبرة 7 بوصة</td><td>1</td></tr>
                                    </tbody>
                                </table>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="أدوات بضع الفرج">
                                    <div class="image-caption">مجموعة أدوات بضع الفرج الجراحية</div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container mt-4">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Episiotomy.svg/600px-Episiotomy.svg.png" alt="بضع الفرج">
                            <div class="image-caption">أنواع بضع الفرج: الأوسط والجانبي الأوسط</div>
                        </div>
                    </div>
                </div>

                <div class="card">
                    <div class="card-header">الإجراءات التمريضية أثناء الولادة</div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="procedure-step">
                                    <div class="english-text">Check good place, light & complete equipment</div>
                                    <div class="arabic-text">التأكد من مكان مناسب، إضاءة ومعدات كاملة</div>
                                    <small class="text-muted">لتسهيل خطوات الإجراء</small>
                                </div>
                                <div class="procedure-step">
                                    <div class="english-text">Put mother in lithotomy position</div>
                                    <div class="arabic-text">وضع الأم في وضعية الوالدة (ليتوتومي)</div>
                                    <small class="text-muted">لتوسيع المنطقة وتسهيل الولادة</small>
                                </div>
                                <div class="procedure-step">
                                    <div class="english-text">Identify signs of 2nd stage of labor</div>
                                    <div class="arabic-text">تحديد علامات المرحلة الثانية من المخاض</div>
                                    <small class="text-muted">لمنع إطالة المرحلة الثانية من المخاض</small>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="image-container">
                                    <img src="https://images.unsplash.com/photo-1559757175-0eb30cd8c063?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="إجراءات التمريض">
                                    <div class="image-caption">الإجراءات التمريضية المنظمة أثناء الولادة</div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="image-container mt-4">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/Birth-symbol.svg/500px-Birth-symbol.svg.png" alt="رمز الولادة">
                            <div class="image-caption">المرحلة الثانية من المخاض: خروج الجنين</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="col-lg-4">
                <div class="sticky-sidebar">
                    <div class="card">
                        <div class="card-header">ملقط الولادة (Delivery Forceps)</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Obstetrical_forceps.JPG/400px-Obstetrical_forceps.JPG" alt="ملقط الولادة">
                                <div class="image-caption">ملقط الولادة الجراحي</div>
                            </div>
                            
                            <h6 class="mt-3">استخدامات ملقط الولادة:</h6>
                            <ul>
                                <li>المرحلة الثانية المطولة من المخاض</li>
                                <li>مؤشرات أمومية مثل ضائقة الأم أو أمراض الأم</li>
                                <li>مؤشرات جنينية مثل ضائقة الجنين</li>
                                <li>توقف تقدم الولادة</li>
                                <li>حالات التعب الأمومي</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="card mt-4">
                        <div class="card-header">المضخات المهبلية (Vacuum Extractors)</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Vacuum_extraction_delivery.jpg/400px-Vacuum_extraction_delivery.jpg" alt="المضخة المهبلية">
                                <div class="image-caption">المضخة المهبلية للمساعدة في الولادة</div>
                            </div>
                            
                            <h6 class="mt-3">مميزات المضخة المهبلية:</h6>
                            <ul>
                                <li>تتطلب تخديرًا أقل من الملقط</li>
                                <li>أقل احتمالية لإصابة قناة الولادة</li>
                                <li>مناسبة لولادة الرأس عند مستوى منخفض</li>
                                <li>تقلل من الحاجة إلى الولادة القيصرية</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="card mt-4">
                        <div class="card-header">بعد الولادة مباشرة</div>
                        <div class="card-body">
                            <div class="image-container">
                                <img src="https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="العناية بعد الولادة">
                                <div class="image-caption">العناية بالأم والمولود بعد الولادة مباشرة</div>
                            </div>
                            
                            <ul class="mt-3">
                                <li>مساعدة الطبيب في إخراج المشيمة</li>
                                <li>فحص المشيمة (الجزء الجنيني والأمومي)</li>
                                <li>إعطاء ميثارجين حسب إرشادات الطبيب</li>
                                <li>العناية بمنطقة العجان وتغيير المنشفة تحت الأم</li>
                                <li>مساعدة الطبيب في إصلاح بضع الفرج</li>
                                <li>التأكد من تقلص الرحم جيدًا</li>
                                <li>التنظيف بالبيتادين على موقع بضع الفرج</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- قسم الأدوات الجراحية -->
        <div class="section-header">
            <h2><i class="fas fa-tools me-2"></i>الأدوات الجراحية في التوليد وأمراض النساء</h2>
        </div>

        <div class="row">
            <!-- ملقط أليس -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">ملقط أليس</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Allis_clamp.jpg/300px-Allis_clamp.jpg" alt="ملقط أليس" class="instrument-image">
                        <div class="english-text">Allis Forceps</div>
                        <div class="arabic-text">ملقط أليس</div>
                        <p class="mt-2">لإمساك التراكيب القوية في العمليات مثل استئصال الرحم البطني</p>
                    </div>
                </div>
            </div>
            
            <!-- ملقط بابكوك -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">ملقط بابكوك</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Babcock_forceps.jpg/300px-Babcock_forceps.jpg" alt="ملقط بابكوك" class="instrument-image">
                        <div class="english-text">Babcock's Forceps</div>
                        <div class="arabic-text">ملقط بابكوك</div>
                        <p class="mt-2">لإمساك التراكيب الأنبوبية مثل قناة فالوب، الطرف غير رضي</p>
                    </div>
                </div>
            </div>
            
            <!-- ملقط كوخر -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">ملقط كوخر</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Kocher_clamp.jpg/300px-Kocher_clamp.jpg" alt="ملقط كوخر" class="instrument-image">
                        <div class="english-text">Kocher's Forceps</div>
                        <div class="arabic-text">ملقط كوخر</div>
                        <p class="mt-2">يستخدم في استئصال قناة فالوب أو المبيض وربط الحبل السري</p>
                    </div>
                </div>
            </div>
            
            <!-- منظار كوسكو -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">منظار كوسكو</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/CuscoSpeculum.jpg/300px-CuscoSpeculum.jpg" alt="منظار كوسكو" class="instrument-image">
                        <div class="english-text">Cusco's Speculum</div>
                        <div class="arabic-text">منظار كوسكو</div>
                        <p class="mt-2">لفحص المهبل وعنق الرحم وأخذ لطاخة بابا نيكولاوا</p>
                    </div>
                </div>
            </div>
            
            <!-- منظار سيمز -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">منظار سيمز</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Sims_speculum.png/300px-Sims_speculum.png" alt="منظار سيمز" class="instrument-image">
                        <div class="english-text">Sims' Speculum</div>
                        <div class="arabic-text">منظار سيمز</div>
                        <p class="mt-2">يستخدم في التوسيع والكحت واستئصال الرحم المهبلي</p>
                    </div>
                </div>
            </div>
            
            <!-- مشرط أير -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">مشرط أير</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/06/Ayre_spatula.jpg/300px-Ayre_spatula.jpg" alt="مشرط أير" class="instrument-image">
                        <div class="english-text">Ayre's Spatula</div>
                        <div class="arabic-text">مشرط أير</div>
                        <p class="mt-2">جهاز لجمع لطاخة بابا نيكولاوا، يتم تدويره 360 درجة</p>
                    </div>
                </div>
            </div>
            
            <!-- ملقط الشريان -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">ملقط الشريان</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Artery_forceps.jpg/300px-Artery_forceps.jpg" alt="ملقط الشريان" class="instrument-image">
                        <div class="english-text">Artery Forceps</div>
                        <div class="arabic-text">ملقط الشريان</div>
                        <p class="mt-2">جهاز لإيقاف النزيف يستخدم للضغط على الأوعية الدموية</p>
                    </div>
                </div>
            </div>
            
            <!-- حامل الإبرة -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card h-100 text-center">
                    <div class="card-header">حامل الإبرة</div>
                    <div class="card-body">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Needle_holder.jpg/300px-Needle_holder.jpg" alt="حامل الإبرة" class="instrument-image">
                        <div class="english-text">Needle Holder</div>
                        <div class="arabic-text">حامل الإبرة</div>
                        <p class="mt-2">يستخدم لحمل إبر الخياطة الجراحية أثناء العمليات</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- تذييل الصفحة -->
    <footer class="text-center">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h4>المراجعة النهائية</h4>
                    <p>للتمريض النسائي والتوليد</p>
                    <p>جمع وتنظيم للمحتوى التعليمي مع الترجمة العربية والصور التوضيحية</p>
                </div>
                <div class="col-md-4">
                    <h5>المحتوى يشمل:</h5>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-check me-2"></i> العناية بمنطقة العجان</li>
                        <li><i class="fas fa-check me-2"></i> الفحص البطني أثناء الحمل</li>
                        <li><i class="fas fa-check me-2"></i> الفحص المهبلي</li>
                        <li><i class="fas fa-check me-2"></i> التعامل مع المرحلة الثانية من المخاض</li>
                        <li><i class="fas fa-check me-2"></i> الأدوات الجراحية في التوليد</li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>مصادر الصور:</h5>
                    <ul class="list-unstyled">
                        <li><i class="fab fa-wikipedia-w me-2"></i> ويكيميديا كومنز</li>
                        <li><i class="fab fa-unsplash me-2"></i> Unsplash</li>
                        <li><i class="fas fa-images me-2"></i> مصادر تعليمية طبية</li>
                    </ul>
                </div>
            </div>
            <hr class="my-4" style="border-color: rgba(255,255,255,0.2);">
            <p class="mb-0">© 2023 المراجعة النهائية - التمريض النسائي والتوليد | إعداد: طاقم التمريض التعليمي</p>
            <p class="mt-2">جميع الصور ذات تراخيص مجانية للاستخدام التعليمي</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    
    <!-- Smooth Scroll -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if(targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if(targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 70,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // تحسين عرض الصور عند التمرير
        window.addEventListener('scroll', function() {
            const images = document.querySelectorAll('.image-container img');
            images.forEach(img => {
                const rect = img.getBoundingClientRect();
                if(rect.top < window.innerHeight && rect.bottom > 0) {
                    img.style.opacity = '1';
                }
            });
        });
        
        // تهيئة الصور عند التحميل
        document.addEventListener('DOMContentLoaded', function() {
            const images = document.querySelectorAll('.image-container img');
            images.forEach(img => {
                img.style.opacity = '0.8';
                img.style.transition = 'opacity 0.5s ease';
            });
        });
    </script>
</body>
</html>
