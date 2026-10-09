# Boris Biriukov

**AI Product Engineer / AI Solutions Engineer**

Full-stack · AI automation · Product discovery · System architecture

[English CV](#english-cv) · [Резюме на русском](#резюме-на-русском) · [English PDF](https://drive.google.com/file/d/12HEBajxhkBneth0Zkm5AndxGIJbmsrjv/view) · [PDF на русском](https://drive.google.com/file/d/1-NGW0Iyex2MrI-FeZLRjVeZhxh2S8Wpb/view)

---

## English CV

**11 years building digital products for businesses.** I independently identify problems, propose solutions, design UX/UI, engineer frontend/backend systems, integrate AI and APIs, and deliver working products. I can assemble and lead a small team when needed. Married, two children. Available for remote work.

**Experience:** 11 years of product engineering · **YouDo:** [205 reviews since 2017, 4.96/5 rating, 189 completed jobs](https://youdo.com/u2767574)

**Contact:** [sovgorec@gmail.com](mailto:sovgorec@gmail.com) · [Portfolio: 1rl.ru](https://1rl.ru/) · [YouDo](https://youdo.com/u2767574)

### Professional experience & selected projects

#### Meraiq · AI-powered HR assessment platform — 2025–2026

Turned an initial high-level brief into the architecture and a launched commercial HR platform. Personally delivered approximately **90–95%** of the product, covering UX/UI, full-stack engineering, psychometric scoring, AI and production rollout; involved a backend specialist for focused tasks.

- **6 user roles:** employers, candidates, employees, psychologists and two administrative access levels. End-to-end workflows for vacancies, invitations, assessments and results access.
- **31 question and task types:** interactive psychometric exercises, multi-stage assessment flows, timers, autosave and session recovery.
- **Unified scoring engine:** IQ/STEN norms, formulas, scales and methodology plugins; parity checks between preview calculations and final reports.
- **5 analytical reporting formats:** individual and group results, candidate comparisons and 360-degree assessments; interactive charts and HTML/PDF/DOCX exports.
- **AI and billing:** AI-based result analysis, test recommendations for job openings, configurable prompts, YooKassa integration, subscription plans and paid reports.
- **Engineering scale:** 125 Prisma data models; CI documentation records **1,460 passing unit/integration tests**, plus regression checks and automated deployment.

**Outcome:** Customer accepted the platform; it went live in 2026.  
**Stack:** Next.js · TypeScript · PostgreSQL · Prisma · Redis · BullMQ · OpenRouter AI.

#### Patent Resolve / USPTO · AI and SEO/GEO — 2026

Identified a narrow commercial opportunity: helping US patent applicants understand USPTO Office Actions, objections and response deadlines. Independently researched, architected and launched an English-language MVP with PDF analysis and a lead-generation funnel.

- **30+ targeted pages:** built intent-driven SEO/GEO content clusters, internal links, structured data, sitemap and llms.txt for discoverability in search engines and AI assistants.
- **PDF documents up to 25 MB / 60 pages:** secure upload and extraction of application numbers, dates, action types, rejection grounds and evidence references.
- **Hybrid AI pipeline:** deterministic document parsing combined with an OpenRouter LLM. The LLM explains the contents; a separate rule-based engine calculates response deadlines. Conflicts require human review.
- **End-to-end workflow:** private file storage, retryable background jobs, PostgreSQL, an internal lead-management console, email and Telegram notifications.
- **Early SEO traction:** 750 search impressions, 5 organic clicks and an average Google Search Console position of **12.6** in less than one month after launch.
- **Commercial hypothesis:** niche patent-response inquiries could generate **$5k–8k per initial engagement**; no actual client revenue is claimed.

**Outcome:** Independently moved from niche research and idea to a live product and initial organic search visibility.  
**Website:** [patent-resolve.pro](https://patent-resolve.pro/)  
**Stack:** Next.js · TypeScript · PostgreSQL · OpenRouter · Docker · SEO/GEO.

#### IFM · Industrial e-commerce and AI automation — 2025

Asked to replicate the functionality and content depth of a complex industrial equipment catalog. Independently built the full pipeline: one-time scraping, structured storage, AI translation, an online store and bulk Avito listings.

- **13,735 products across 775 categories:** wrote a Playwright scraper for images, SKUs, prices, category hierarchy and specifications; stored the structured catalog in PostgreSQL.
- **481,833 technical data rows:** parsed nested tables and detailed specifications, preparing them for product pages and multi-attribute filtering.
- **AI localization EN → RU:** implemented batch translation via OpenRouter with database caching, protecting product codes, numeric values and technical standards.
- **Next.js online store:** delivered catalog, search, detailed specification tables, filters, cart and Telegram order notifications. Database snapshot includes **4,901 filter configuration entries**.
- **Avito automation:** prepared bulk product publishing via API with photos and AI-generated sales copy based on catalog data.
- **Approximately 40 completed sales in the first 2 weeks** after Avito listings went live, according to customer feedback.

**Outcome:** Delivered the complete workflow from scraper and PostgreSQL to AI localization, e-commerce and Avito sales.  
**Stack:** Playwright · Node.js · Next.js · TypeScript · PostgreSQL · OpenRouter · Telegram API.

#### Park Nedvizhimost · Real estate platform — 2024–2026

Proposed an integrated set of digital products to a real-estate agency and led product and technical delivery: data collection, full-stack platform, CRM, valuations and AI assistants.

- **250,000+ properties:** developed a multithreaded nationwide data scraper with an approximately **7-day refresh cycle**; ID-based synchronization, price/attribute updates and a continuously updated PostgreSQL database.
- **Full-stack platform:** React, Next.js and Node.js; separate primary and secondary housing catalogs, CRM, two-factor authentication and custom content/parser administration.
- **Custom UI/UX:** designed advanced search filters, listings, photo galleries, responsive interfaces and microinteractions in Figma.
- **Property valuation service:** integrated CIAN API, Telegram authentication and online payments.
- **2 Telegram AI bots:** property recommendations with voice input and favorites; monitoring, ChatGPT/Gemini rewriting, content generation and channel publishing.

**Responsibilities:** Product hypotheses · architecture · UX/UI · full-stack · AI/API.  
**Status:** Data scraper is running; main web platform is in final development and customer acceptance.

#### LOYQUP · Construction crowdfunding platform — 2023–2026

Led development of a construction-project crowdfunding platform, from product flows and UI prototypes to financial operations and banking integrations. Coordinated a **three-person team**, including myself.

- **3 role-specific portals:** investor, borrower and contractor, with access controls, onboarding, documentation and funding workflows.
- **Investment lifecycle:** applications, investments, loan issuance and repayment, yield and fee calculations, and automated investing.
- **Tochka Bank API:** integrated bank-account operations; the bank extended its API to meet project requirements.
- **Operations console:** document verification, interest-rate management, funding approvals, transaction monitoring, SMS and counterparty validation integrations.
- **Hands-on technical lead:** designed the prototype and UX/UI, implemented components, coordinated React frontend and Django backend engineers; delivered **2 landing pages**.

**Status:** Core financial flows are operational; final testing and customer acceptance are in progress.

#### Construction company ERP — 2023

Mapped workflows across **8 departments serving 150+ employees**. Helped architect an ERP to consolidate **34 Excel/Google Sheets**, from estimates and purchasing to inventory and field crews.

- **Business discovery:** learned domain processes and prepared a functional prototype within **3 weeks**; designed UX/UI in Figma and contributed to frontend/backend implementation.
- **Estimate parser:** imported large Excel files and converted rows into structured ERP records, replacing manual re-entry with human verification.
- **Purchasing automation:** normalized vendor quotes, compared prices, selected suppliers, generated invoices for selected items and sent them by email.
- **Field operations and inventory:** mobile interface for crew supervisors; material usage allocation by worker and shift; approximately **20 modules** including CRM, stock and analytics.

**Illustrative estimate, not a measured outcome:** Potential 4.5–8 hours saved per 1,000-row estimate. Final client-wide ERP adoption is unverified.

#### Roscosmos · Sfera industry event — 2022

Delivered the end-to-end website for an event organized by a Roscosmos subsidiary: information architecture, prototype, design, responsive development and launch.

- **10+ design iterations:** created several directions, including a futuristic concept not used in the final release.
- **7 client stakeholders:** presented decisions, reconciled competing requirements and completed approval.
- **End-to-end delivery:** HTML/CSS, animation, WordPress integration and training for the content team; website presented at an industry forum.

**Outcome:** Positive client feedback and invitations to subsequent projects.

#### Cristall Group · Growth experiments — 2019–2020

Combined product thinking, digital engineering and marketing: evaluated real-estate opportunities, built acquisition tools and measured demand with live campaigns.

- **Approximately 200 new-build property leads/month at RUB 430 per lead** versus an indicative RUB 2,500 market benchmark at the time.
- **Approximately 200 commercial-property owner inquiries over 6 months** through a self-developed long-tail SEO strategy.
- **3 SEO landing pages:** targeted Pyaterochka, VkusVill and Gorzdrav property leasing searches; first organic leads arrived after roughly 2 weeks without paid search.
- **Business experiments:** tested new-build sales, resale, buyouts, leasing and interior design; built websites, coordinated contractors and contributed to sales strategy.

**Initial engagement:** 48 leads over 14 days after optimizing ads, at about RUB 2,000 per lead.

### What I build

Business process automation · AI agents and LLM integrations · Full-stack web applications · Product architecture · Scrapers and data pipelines · API / CRM / ERP integrations · Internal tools and dashboards · UX/UI and clickable prototypes · Telegram bots · Databases and analytics · MVPs and hypothesis testing · Payments and banking APIs · Technical leadership · Legacy system modernization.

**Languages:** Russian — native · English — Upper-Intermediate · Spanish — A2.

---

## Резюме на русском

<details>
<summary><strong>Развернуть полное резюме на русском / Expand Russian CV</strong></summary>

### Борис Бирюков

**AI Product Engineer / AI Solutions Engineer**

Full-stack · AI automation · Product discovery · System architecture

**11 лет создаю цифровые решения для бизнеса.** Сам разбираюсь в задаче, предлагаю идею, проектирую UX/UI, разрабатываю frontend/backend, подключаю AI и API, запускаю результат. При необходимости собираю и веду команду. Женат, двое детей. Доступен для удалённой работы.

**11 лет продуктовой разработки** · **[YouDo: 205 отзывов, с 2017 года, оценка 4,96/5, 189 выполненных заданий](https://youdo.com/u2767574)**

**Контакты:** [sovgorec@gmail.com](mailto:sovgorec@gmail.com) · [1rl.ru](https://1rl.ru/) · [YouDo](https://youdo.com/u2767574)

### Проекты и опыт

#### Мера IQ (Meraiq) — 2025–2026

Из общего ТЗ сформировал продуктовую архитектуру и самостоятельно реализовал **≈90–95% коммерческой HR-платформы**: от UI/UX и backend до AI, расчётов и запуска. Backend-специалиста привлекал точечно.

- **6 ролей пользователей:** работодатель, кандидат, сотрудник, психолог и два уровня администрирования. Вакансии, приглашения, прохождение тестов и доступ к результатам.
- **31 тип заданий:** интерактивные психометрические методики, многоэтапные сценарии, таймеры, автосохранение и восстановление тестирования.
- **Единый расчётный движок:** IQ/STEN, формулы, нормы и шкалы; подключаемые методики, проверка совпадения расчётов между preview и итоговыми отчётами.
- **5 видов аналитических отчётов:** индивидуальные, групповые, сравнение кандидатов и оценка 360°; графики, экспорт HTML/PDF/DOCX.
- **AI и платежи:** анализ результатов, подбор методик по вакансии, настраиваемые промпты, интеграция ЮKassa, тарифы и платные отчёты.
- **Инженерный масштаб:** 125 моделей Prisma; в документации CI зафиксированы **1 460 успешных unit/integration-тестов**, настроены регрессии и деплой.

**Результат:** платформа принята заказчиком и запущена в 2026 году.  
**Стек:** Next.js · TypeScript · PostgreSQL · Prisma · Redis · BullMQ · OpenRouter AI.

#### Patent Resolve / USPTO · AI и SEO/GEO — 2026

Сам нашёл узкую бизнес-гипотезу: помогать заявителям USPTO, получившим Office Action, разобраться с основаниями замечаний и сроками ответа. Полностью спроектировал и запустил англоязычный MVP с AI-анализом PDF и воронкой обращений.

- **30+ тематических страниц:** построил SEO/GEO-архитектуру под конкретные запросы и намерения, контентные кластеры, внутренние ссылки, структурированные данные, sitemap и llms.txt.
- **Анализ документов до 25 МБ / 60 страниц:** безопасная загрузка PDF, извлечение номера заявки, даты, типа действия, оснований отказа и ссылок на страницы источника.
- **Гибридный AI-пайплайн:** детерминированный разбор документа + LLM через OpenRouter. Модель объясняет содержание, а сроки ответа рассчитываются отдельным алгоритмом; спорные факты требуют проверки человеком.
- **Полный workflow:** приватное хранение файлов, фоновые задачи с повторными попытками, PostgreSQL, внутренняя панель обработки обращений, email и Telegram-уведомления.
- **Ранний SEO-результат:** 750 показов, 5 органических кликов и средняя позиция **12,6** в Google Search Console менее чем за месяц после запуска — без исторического авторитета домена.
- **Бизнес-гипотеза:** нишевые обращения по патентным вопросам с потенциальным чеком первой услуги **$5–8 тыс.**; реальные сделки на текущем этапе не заявляются.

**Результат:** самостоятельно прошёл путь от исследования ниши и идеи до работающего продукта и первых показов в поиске.  
**Сайт:** [patent-resolve.pro](https://patent-resolve.pro/) · **Стек:** Next.js · TypeScript · PostgreSQL · OpenRouter · Docker · SEO/GEO.

#### IFM · промышленный e-commerce и AI-автоматизация — 2025

Получил задачу создать интернет-магазин по примеру сложного каталога производителя. Сам разработал цепочку от разового сбора и локализации данных до полнофункционального магазина и массового размещения товаров на Авито.

- **13 735 товаров и 775 категорий:** написал разовый парсер на Playwright, собрал изображения, артикулы, цены, иерархию каталога и характеристики; структурировал данные в PostgreSQL.
- **481 833 строки технических данных:** обработал вложенные таблицы и спецификации; подготовил данные для карточек товаров и многопараметрической фильтрации.
- **AI-перевод EN → RU:** настроил пакетный перевод через OpenRouter с кэшем в БД; защитил от перевода артикулы, числа и технические стандарты.
- **Интернет-магазин на Next.js:** реализовал каталог, поиск, карточки со сложными таблицами, фильтры, корзину и оформление заказов с уведомлением в Telegram. В базе — **4 901 настройка фильтров**.
- **Авито:** организовал массовую выгрузку через API с фотографиями и нейросетевой генерацией продающих текстов на основе данных каталога.
- **≈40 оформленных продаж за первые 2 недели** после публикации товаров на Авито — по обратной связи заказчика.

**Результат:** самостоятельно запустил связку «парсер → PostgreSQL → AI-локализация → магазин → Авито».  
**Стек:** Playwright · Node.js · Next.js · TypeScript · PostgreSQL · OpenRouter · Telegram API.

#### Парк Недвижимость — 2024–2026

Сам предложил агентству недвижимости комплекс цифровых решений и взял на себя продуктовую и техническую реализацию: сбор данных, платформу, CRM, сервис оценки и AI-инструменты.

- **250 000+ объектов:** разработал многопоточный парсер по регионам России; цикл сбора **≈7 дней**. Синхронизация по ID, обновление цен и характеристик, актуальная PostgreSQL-база.
- **Full-stack платформа:** React, Next.js, Node.js; раздельные каталоги первичной и вторичной недвижимости, CRM, 2FA и своя админка для контента и управления парсером.
- **Собственный UI/UX:** спроектировал в Figma сложные фильтры, карточки, фотогалереи, адаптивные экраны и микроанимации.
- **Сервис онлайн-оценки:** интеграция с API ЦИАН, вход через Telegram, приём платежей.
- **2 AI-бота в Telegram:** подбор объектов с голосовым вводом и избранным; мониторинг источников, рерайтинг через ChatGPT/Gemini, генерация материалов и публикация.

**Роль:** продуктовые гипотезы · архитектура · UI/UX · full-stack · AI/API.  
**Статус:** парсер работает; веб-платформа находится на финальном этапе разработки и приёмки.

#### ЛОЙК АП (LOYQUP) — 2023–2026

Вёл разработку краудфандинговой платформы для строительных проектов: от прототипов и сценариев до сложной финансовой логики и интеграций с банком. Организовал работу **команды из трёх человек**.

- **3 личных кабинета:** инвестор, заёмщик, подрядчик — разные права, регистрация, документы и процессы финансирования.
- **Финансовый цикл:** обработка заявок, инвестиции, выдача и возврат займов, расчёт доходности и комиссий, механизм автоинвестирования.
- **Банк «Точка»:** интеграция API операций со счетами; под задачи платформы банк дополнительно доработал API.
- **Администрирование:** проверка документов, назначение ставок, согласование финансирования, контроль операций; интеграции SMS и проверки реквизитов.
- **Личная ответственность:** разработал прототип и UI/UX, участвовал в технической реализации, руководил frontend- (React) и backend-разработчиком (Django); сделал **2 лендинга**.

**Статус:** финансовые сценарии работоспособны; продолжаются финальное тестирование и приёмка.

#### ERP для строительной компании — 2023

Погрузился в процессы **8 отделов строительной компании (150+ сотрудников)**. Проектировал ERP для объединения **34 Excel/Google-таблиц**: от смет и закупок до склада и бригад.

- **Разбор бизнеса:** за первые **3 недели** изучил предметную область, создал прототип и спроектировал UI/UX в Figma; участвовал во frontend/backend.
- **Парсер смет:** импорт крупных Excel-файлов, извлечение и структурирование строк; вместо ручного переноса — проверка результатов сметчиком.
- **Автоматизация закупок:** разбор предложений, сопоставление цен, выбор поставщиков, формирование счетов по выбранным позициям и отправка email.
- **Учёт смен и материалов:** мобильный интерфейс бригадира, списание и распределение расхода по сотрудникам; всего **≈20 модулей**, включая CRM, склад и аналитику.

**Оценка, не замер:** потенциальная экономия 4,5–8 ч на смете в 1 000 строк. Окончательный ввод ERP в эксплуатацию не подтверждён.

#### Роскосмос · «Сфера» — 2022

Для мероприятия дочерней структуры Роскосмоса самостоятельно прошёл полный цикл: информационная архитектура, прототип, дизайн, разработка адаптивного сайта и запуск.

- **10+ вариантов дизайна:** подготовил концепции, в том числе авторскую футуристическую (не вошла в итоговую версию).
- **7 согласующих:** защищал решения, учитывал требования разных представителей заказчика и довёл интерфейс до утверждения.
- **Запуск под ключ:** HTML/CSS, анимации, WordPress, обучение команды управлению контентом. Сайт представлен на отраслевом форуме.

**Результат:** положительная обратная связь и приглашение к новым проектам.

#### Cristall Group — 2019–2020

Работал на стыке маркетинга, продукта и разработки: исследовал направления недвижимости, предлагал гипотезы, создавал цифровые инструменты и проверял результат на реальных заявках.

- **≈200 заявок в месяц** на новостройки Москвы по **430 ₽** — против рыночного ориентира **≈2 500 ₽** за заявку на тот период.
- **≈200 обращений за 6 месяцев** от собственников коммерческих помещений благодаря самостоятельно разработанной SEO-гипотезе.
- **3 SEO-лендинга:** под «Пятёрочку», «ВкусВилл» и «Горздрав»; первые органические обращения примерно через 2 недели, без контекстной рекламы.
- **Бизнес-инициативы:** тестировал новостройки, вторичку, выкуп, аренду и дизайн интерьеров; самостоятельно делал сайты, привлекал подрядчиков, участвовал в стратегии продаж.

**Старт сотрудничества:** 48 заявок за 14 дней после настройки рекламы, ≈2 000 ₽ за заявку.

### Какие задачи беру

Аудит и автоматизация процессов · AI-агенты и LLM-интеграции · Full-stack веб-сервисы · Архитектура продуктов · Парсеры и обработка данных · API / CRM / ERP-интеграции · Внутренние CRM и админки · UI/UX и интерактивные прототипы · Боты Telegram · Базы данных и аналитика · MVP и тестирование гипотез · Интеграция платежей и банковских API · Управление разработкой · Доработка действующих систем.

**Языки:** Русский — родной · Английский — Upper-Intermediate · Испанский — A2.

</details>

---

**[Portfolio / Портфолио](https://1rl.ru/)** · **[English PDF](https://drive.google.com/file/d/12HEBajxhkBneth0Zkm5AndxGIJbmsrjv/view)** · **[Русский PDF](https://drive.google.com/file/d/1-NGW0Iyex2MrI-FeZLRjVeZhxh2S8Wpb/view)**
