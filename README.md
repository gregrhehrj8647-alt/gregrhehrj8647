<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>체육계열 진로 & 신체구조 탐색센터</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        nav {
            background-color: #333;
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #667eea;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .career-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .career-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: pointer;
        }

        .career-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        .career-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem;
            text-align: center;
        }

        .career-header h3 {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
        }

        .career-content {
            padding: 1.5rem;
        }

        .career-content h4 {
            color: #667eea;
            margin-top: 1rem;
            margin-bottom: 0.5rem;
        }

        .career-content p {
            font-size: 0.95rem;
            margin-bottom: 0.5rem;
        }

        .body-system {
            background-color: #f9f9f9;
            padding: 0.5rem 1rem;
            border-left: 4px solid #667eea;
            margin: 0.5rem 0;
            border-radius: 4px;
        }

        .section-title {
            font-size: 2rem;
            color: #333;
            margin: 2rem 0 1rem 0;
            border-bottom: 3px solid #667eea;
            padding-bottom: 0.5rem;
        }

        .info-box {
            background-color: #e8f4f8;
            border-left: 5px solid #667eea;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
        }

        .info-box strong {
            color: #667eea;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        .anatomy-section {
            background: white;
            padding: 2rem;
            margin: 1rem 0;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .anatomy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin: 1rem 0;
        }

        .system-card {
            border: 2px solid #667eea;
            border-radius: 8px;
            padding: 1.5rem;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }

        .system-card h4 {
            color: #667eea;
            margin-bottom: 0.5rem;
        }

        .system-card ul {
            list-style-position: inside;
            color: #555;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.8rem;
            }

            nav ul {
                flex-direction: column;
                gap: 1rem;
            }

            .career-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- 헤더 -->
    <header>
        <h1>🏃 체육계열 진로 & 신체구조 탐색센터</h1>
        <p>체육 교과와 생명과학을 연계한 진로 탐색 플랫폼</p>
    </header>

    <!-- 네비게이션 -->
    <nav>
        <ul>
            <li><a href="#careers">진로분야</a></li>
            <li><a href="#anatomy">신체구조</a></li>
            <li><a href="#connections">교과연계</a></li>
            <li><a href="#resources">학습자료</a></li>
        </ul>
    </nav>

    <!-- 메인 컨텐츠 -->
    <div class="container">
        <!-- 진로분야 섹션 -->
        <section id="careers">
            <h2 class="section-title">🎯 체육계열 진로분야</h2>
            <div class="career-grid">
                <!-- 진로 1: 운동선수 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>🏅 운동선수</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 다양한 스포츠 종목에서 전문성을 갖춘 선수</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>근육계:</strong> 근력, 근지구력 발달
                        </div>
                        <div class="body-system">
                            <strong>순환계:</strong> 심폐기능, 산소운반능력
                        </div>
                        <div class="body-system">
                            <strong>신경계:</strong> 반응속도, 협응력
                        </div>
                        <h4>관련 교과:</h4>
                        <p>체육 (운동기능), 생명과학 (근육구조, 에너지대사)</p>
                    </div>
                </div>

                <!-- 진로 2: 스포츠의학 전문가 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>⚕️ 스포츠의학 전문가</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 운동선수의 부상 예방 및 치료 전문가</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>근골격계:</strong> 뼈, 관절, 인대 구조
                        </div>
                        <div class="body-system">
                            <strong>신경계:</strong> 신경손상 진단
                        </div>
                        <h4>관련 교과:</h4>
                        <p>생명과학 (인체해부, 생리), 보건</p>
                    </div>
                </div>

                <!-- 진로 3: 피트니스 트레이너 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>💪 피트니스 트레이너</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 개인 맞춤형 운동 프로그램 설계 및 지도</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>근육계:</strong> 근력 향상, 체형 관리
                        </div>
                        <div class="body-system">
                            <strong>순환계:</strong> 유산소 운동 능력
                        </div>
                        <div class="body-system">
                            <strong>호흡계:</strong> 호흡 효율성
                        </div>
                        <h4>관련 교과:</h4>
                        <p>체육 (운동프로그래밍), 생명과학 (근육대사)</p>
                    </div>
                </div>

                <!-- 진로 4: 체육교사 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>📚 체육교사</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 학생들에게 체육 교과 및 건강지식 전달</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>전신계통:</strong> 신체발달, 건강관리
                        </div>
                        <h4>관련 교과:</h4>
                        <p>체육 (전공), 생명과학 (건강교육)</p>
                    </div>
                </div>

                <!-- 진로 5: 스포츠영양사 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>🥗 스포츠영양사</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 운동선수의 영양 관리 및 식단 설계</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>소화계:</strong> 영양소 흡수
                        </div>
                        <div class="body-system">
                            <strong>에너지대사:</strong> 운동 에너지 공급
                        </div>
                        <h4>관련 교과:</h4>
                        <p>생명과학 (소화, 대사), 보건</p>
                    </div>
                </div>

                <!-- 진로 6: 스포츠 심리상담가 -->
                <div class="career-card">
                    <div class="career-header">
                        <h3>🧠 스포츠 심리상담가</h3>
                    </div>
                    <div class="career-content">
                        <p><strong>설명:</strong> 운동선수의 심리 관리 및 성능 향상</p>
                        <h4>관련 신체계통:</h4>
                        <div class="body-system">
                            <strong>신경계:</strong> 뇌, 신경전달물질
                        </div>
                        <div class="body-system">
                            <strong>내분비계:</strong> 호르몬과 스트레스
                        </div>
                        <h4>관련 교과:</h4>
                        <p>생명과학 (신경계, 내분비계), 심리</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 신체구조 섹션 -->
        <section id="anatomy">
            <h2 class="section-title">🫀 신체구조 & 생명과학 연계</h2>
            <div class="anatomy-section">
                <h3>주요 신체 계통과 스포츠의 관계</h3>
                <div class="anatomy-grid">
                    <!-- 근육계 -->
                    <div class="system-card">
                        <h4>💪 근육계 (Muscular System)</h4>
                        <p><strong>구성:</strong> 골격근, 심근, 평활근</p>
                        <p><strong>기능:</strong> 운동, 자세유지, 열 발생</p>
                        <ul>
                            <li>운동선수: 근력·근지구력 개발</li>
                            <li>대사: 운동 에너지 공급</li>
                            <li>적응: 훈련을 통한 근비대</li>
                        </ul>
                    </div>

                    <!-- 순환계 -->
                    <div class="system-card">
                        <h4>❤️ 순환계 (Circulatory System)</h4>
                        <p><strong>구성:</strong> 심장, 혈관, 혈액</p>
                        <p><strong>기능:</strong> 산소·영양분 운반, 폐기물 제거</p>
                        <ul>
                            <li>심폐기능: VO₂ Max 향상</li>
                            <li>산소운반: 운동 능력 결정</li>
                            <li>훈련효과: 심장크기 증가</li>
                        </ul>
                    </div>

                    <!-- 호흡계 -->
                    <div class="system-card">
                        <h4>🫁 호흡계 (Respiratory System)</h4>
                        <p><strong>구성:</strong> 폐, 기관지, 횡격막</p>
                        <p><strong>기능:</strong> 산소 흡수, 이산화탄소 배출</p>
                        <ul>
                            <li>호흡량: 운동 중 증가</li>
                            <li>환기능력: 훈련으로 개선</li>
                            <li>산소효율: 지구력 관련</li>
                        </ul>
                    </div>

                    <!-- 신경계 -->
                    <div class="system-card">
                        <h4>🧠 신경계 (Nervous System)</h4>
                        <p><strong>구성:</strong> 뇌, 척수, 신경</p>
                        <p><strong>기능:</strong> 자극 감지 및 반응</p>
                        <ul>
                            <li>반응속도: 운동 경기력 향상</li>
                            <li>협응력: 운동기술 발전</li>
                            <li>학습: 근육기억 형성</li>
                        </ul>
                    </div>

                    <!-- 골격계 -->
                    <div class="system-card">
                        <h4>🦴 골격계 (Skeletal System)</h4>
                        <p><strong>구성:</strong> 뼈, 연골, 인대</p>
                        <p><strong>기능:</strong> 신체 지지, 보호, 혈구생성</p>
                        <ul>
                            <li>골밀도: 운동으로 증가</li>
                            <li>부상관리: 염좌, 탈구 예방</li>
                            <li>성장: 청소년기 발달</li>
                        </ul>
                    </div>

                    <!-- 내분비계 -->
                    <div class="system-card">
                        <h4>⚖️ 내분비계 (Endocrine System)</h4>
                        <p><strong>구성:</strong> 호르몬 분비 기관들</p>
                        <p><strong>기능:</strong> 호르몬을 통한 조절</p>
                        <ul>
                            <li>성장호르몬: 근육 발달 촉진</li>
                            <li>인슐린: 에너지 조절</li>
                            <li>코르티솔: 스트레스 반응</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- 교과연계 섹션 -->
        <section id="connections">
            <h2 class="section-title">📖 체육 & 생명과학 교과 연계</h2>
            <div class="info-box">
                <h3>체육교과와 생명과학의 만남</h3>
                <p>체육 교과는 신체 활동을 통해 건강을 증진하고, 생명과학은 이러한 신체 활동의 원리를 과학적으로 설명합니다.</p>
            </div>

            <div class="anatomy-section">
                <h4>📚 체육 교과 내용</h4>
                <ul style="list-style-position: inside; line-height: 2;">
                    <li>운동기능: 기초기능, 전문기능 습득</li>
                    <li>건강관리: 체력 향상, 건강 유지</li>
                    <li>스포츠 과학: 운동 원리, 훈련 방법</li>
                    <li>안전관리: 부상 예방, 응급처치</li>
                    <li>스포츠 문화: 스포츠 가치, 윤리</li>
                </ul>
            </div>

            <div class="anatomy-section">
                <h4>🔬 생명과학 교과 내용</h4>
                <ul style="list-style-position: inside; line-height: 2;">
                    <li><strong>호흡과 순환:</strong> 산소 운반, 에너지 생산</li>
                    <li><strong>신경과 호르몬:</strong> 신체 조절 및 반응</li>
                    <li><strong>소화와 배설:</strong> 영양소 흡수, 대사 산물 제거</li>
                    <li><strong>근육 수축:</strong> ATP 에너지 사용 원리</li>
                    <li><strong>적응과 진화:</strong> 훈련에 의한 신체 변화</li>
                </ul>
            </div>

            <div class="anatomy-section">
                <h4>🔗 구체적 연계 사례</h4>
                <table style="width: 100%; border-collapse: collapse;">
                    <tr style="background-color: #667eea; color: white;">
                        <td style="padding: 1rem; border: 1px solid #ddd;"><strong>운동 주제</strong></td>
                        <td style="padding: 1rem; border: 1px solid #ddd;"><strong>체육 교과</strong></td>
                        <td style="padding: 1rem; border: 1px solid #ddd;"><strong>생명과학</strong></td>
                    </tr>
                    <tr>
                        <td style="padding: 1rem; border: 1px solid #ddd;">단거리 달리기</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">스타트, 가속, 피니시 기술</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">무산소 호흡, 젖산 축적</td>
                    </tr>
                    <tr style="background-color: #f9f9f9;">
                        <td style="padding: 1rem; border: 1px solid #ddd;">마라톤</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">페이싱, 체력 관리</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">유산소 호흡, 심폐기능</td>
                    </tr>
                    <tr>
                        <td style="padding: 1rem; border: 1px solid #ddd;">근력운동</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">올바른 자세, 근력 향상</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">근비대, 에너지 대사</td>
                    </tr>
                    <tr style="background-color: #f9f9f9;">
                        <td style="padding: 1rem; border: 1px solid #ddd;">스포츠 부상</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">안전 수칙, 부상 관리</td>
                        <td style="padding: 1rem; border: 1px solid #ddd;">근육 손상, 염증 반응</td>
                    </tr>
                </table>
            </div>
        </section>

        <!-- 학습자료 섹션 -->
        <section id="resources">
            <h2 class="section-title">📚 학습자료 & 추천도서</h2>
            <div class="anatomy-section">
                <h4>📖 추천 도서</h4>
                <ul style="list-style-position: inside; line-height: 2.2; font-size: 0.95rem;">
                    <li><strong>'인체의 신비'</strong> - 신체 구조와 기능 이해</li>
                    <li><strong>'스포츠 과학의 이해'</strong> - 운동 원리 학습</li>
                    <li><strong>'체육과 건강'</strong> - 교과 기본 개념</li>
                    <li><strong>'생명과학 I, II'</strong> - 고등학교 교과서</li>
                </ul>
            </div>

            <div class="anatomy-section">
                <h4>🎬 학습 활동</h4>
                <ul style="list-style-position: inside; line-height: 2.2; font-size: 0.95rem;">
                    <li>운동 중 맥박 측정 및 기록</li>
                    <li>신체 부위별 근력 측정</li>
                    <li>호흡량 변화 관찰</li>
                    <li>스포츠 영양 분석</li>
                    <li>부상 사례 연구</li>
                    <li>진로 전문가 인터뷰</li>
                </ul>
            </div>

            <div class="info-box">
                <h4>💡 진로 탐색 팁</h4>
                <p>1. <strong>다양한 스포츠 경험:</strong> 여러 종목을 시도해보세요.</p>
                <p>2. <strong>신체과학 학습:</strong> 생명과학, 해부학 기초 공부하기</p>
                <p>3. <strong>현장 체험:</strong> 스포츠 시설, 의료기관 방문</p>
                <p>4. <strong>전문가 상담:</strong> 현직 전문가와 대화하기</p>
                <p>5. <strong>대학 탐색:</strong> 체육교육, 스포츠과학, 운동과학 학과 조사</p>
            </div>
        </section>
    </div>

    <!-- 푸터 -->
    <footer>
        <p>&copy; 2024 체육계열 진로 & 신체구조 탐색센터</p>
        <p>고등학생 진로 탐색을 위한 교육용 웹사이트</p>
    </footer>
</body>
</html>
