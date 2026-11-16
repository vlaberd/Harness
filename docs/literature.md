# Литература и материалы

Курсы, статьи, книги и другие материалы для освоения роли. Это ответ на раздел чеклиста «Рекомендуемые образовательные материалы».

Список не учебный план компании и не требование грейда. Начинать стоит с тем, где в текущем опыте больше всего пробелов. Внутренние тексты роли стоят раньше внешних: спецификации не содержат правила «обход брокера — инцидент».

Ссылки открыты 16 ноября 2026. Адрес принадлежит сайту названного проекта.

Сначала внутренние тексты:

- [role-v2.md](role-v2.md) — актуальный профиль L5, восемь результатов, границы.
- [role-card.md](role-card.md) — миссия, четыре ядра, гарантии и проверки.
- [grades.md](grades.md) — лестница: до 3 уровня DevOps, вход на 3–4.
- [interview-signals.md](interview-signals.md) — шесть ситуаций и различие уровней 4, 5 и 6.

## Ближе всего к роли

Обе книги — ранний выпуск O'Reilly: текст ещё пишется, оглавление на странице не финальное. Дата на карточке издателя — плановый выход, не признак того, что книга уже закончена.

| Материал | Зачем |
| --- | --- |
| [Nicole Koenigstein. Harness Engineering](https://www.oreilly.com/library/view/harness-engineering/0642572422783/). O'Reilly, ранний выпуск, плановый выход декабрь 2027. Подзаголовок в репозитории автора: Optimization, Coordination, and Adaptive Agentic Systems. Код глав: [Nicolepcx/harness_engineering](https://github.com/Nicolepcx/harness_engineering) | Оболочка как слой надёжности вокруг модели: состояние, навыки, границы доверия, передача между агентами, след, права и аудит. Ближе всего к ядру этой роли |
| [Addy Osmani. Agentic Engineering](https://www.oreilly.com/library/view/agentic-engineering/0642572392291/). O'Reilly, ранний выпуск, плановый выход сентябрь 2027 | Из чего собраны модель, оболочка и цикл: песочница, инструменты, MCP, наблюдаемость, условие остановки. Книга про работу инженера с кодирующими агентами. Эксплуатацию платформы она не заменяет |

## На русском

Официального русского текста MCP, A2A и спецификаций агентной оболочки нет. Ниже издания и статьи, которые закрывают переносимую базу: надёжность, платформу как продукт для внутренних команд и изоляцию сессии. Язык остального списка — английский.

| Материал | Зачем |
| --- | --- |
| Бейер, Джоунс, Петофф, Мёрфи. Site Reliability Engineering. Надежность и безотказность как в Google. Питер, ISBN 978-5-4461-0976-0. [Страница издательства](https://www.piter.com/product/site-reliability-engineering-nadezhnost-i-bezotkaznost-kak-v-google). Фрагмент главы на русском: [Хабр, издательство «Питер»](https://habr.com/ru/companies/piter/articles/420139/) | Тот же текст, что свободное английское издание на sre.google: инцидент, бюджет ошибки, выпуск без героизма. На странице «Питера» в поле года стоит 2027; ISBN — у давно вышедшего русского издания |
| Клеппман, Риккомини. Высоконагруженные приложения. Программирование, масштабирование, поддержка. 2-е изд. Питер, ISBN 978-601-08-6343-9. [Страница издательства](https://www.piter.com/collection/all/product/vysokonagruzhennye-prilozheniya-programmirovanie-masshtabirovanie-podderzhka-2-e-izd-2) | Состояние, журнал, повтор и согласованность. Второе издание переписано вместе с Крисом Риккомини; английская строка ниже в списке указывает на первое издание Клеппмана |
| Нейгард. Release it! Проектирование и дизайн ПО для тех, кому не всё равно. Питер, 2016, ISBN 978-5-496-01611-7. [Страница издательства](https://www.piter.com/collection/A31172/product/release-it-proektirovanie-i-dizayn-po-dlya-teh-komu-ne-vsyo-ravno) | Устойчивость к сбоям, в том числе предохранитель. Это первое издание. Бумажного тиража на странице нет, электронная книга указана. Второе издание — английская ссылка в разделе про надёжность |
| Скелтон, Паис. Топологии команд. 2-е изд. БХВ, ISBN 978-601-12-9651-9, год на странице 2026. [Страница издательства](https://bhv.ru/product/topologii-komand-2-e-izd/) | Платформенная команда и когнитивная нагрузка. На момент проверки бумажный экземпляр не продавался. Читать сейчас можно английский текст на [teamtopologies.com](https://teamtopologies.com/) |
| [Авито. Построение платформенного продукта](https://habr.com/ru/companies/avito/articles/762160/) | Внутренняя платформа как один интерфейс для продуктовых команд, а не набор кластерных кубиков. Близко к тому, как эта роль сидит на корпоративной IDP |
| [Ozon. Одна платформа, чтобы править всеми](https://habr.com/ru/companies/ozontech/articles/708274/) | Слои платформы от железа до сервисов и зачем продуктовой команде не собирать инфраструктуру самой |
| [Yandex Cloud. Сетевые политики Kubernetes](https://yandex.cloud/ru/docs/managed-kubernetes/concepts/network-policy) | Сетевая граница на русском: куда поду можно ходить. Тот же приём, что граница сессии |
| [Yandex Cloud. Безопасность Kubernetes](https://yandex.cloud/ru/docs/security/domains/kubernetes) | Профиль допуска пода, сетевой запрет по умолчанию, политика до запуска. Имена Calico, Cilium и Gatekeeper здесь примеры площадки, не требование роли |

## Устройство среды агентов

| Материал | Зачем |
| --- | --- |
| [Anthropic. Effective harnesses for long-running agents](https://www.anthropic.com/research/effective-harnesses-for-long-running-agents) | Долгая работа и передача результата между сессиями: контрольные точки и файл прогресса |
| [Anthropic. Harness design for long-running apps](https://www.anthropic.com/research/harness-design-long-running-apps) | Разделение работы между агентами и независимая проверка результата |
| [Anthropic. Scaling Managed Agents](https://www.anthropic.com/research/managed-agents) | Разделение истории сессии, управляющего исполнения и изолированной рабочей среды |
| [Anthropic. Building effective agents](https://www.anthropic.com/research/building-effective-agents) | Базовые схемы построения агентов и их совместной работы |

## Протоколы

| Материал | Зачем |
| --- | --- |
| [Документация MCP](https://modelcontextprotocol.io/) | Как к агенту подключаются инструменты и данные |
| [Anthropic Academy. Introduction to Model Context Protocol](https://anthropic.skilljar.com/introduction-to-model-context-protocol) | Короткий практический курс: сервер и клиент MCP. Продолжение на той же площадке — MCP Advanced Topics |
| [Документация A2A](https://a2a-protocol.org/latest/) | Передача задач, состояний и результатов между агентами |
| [DeepLearning.AI. A2A: The Agent2Agent Protocol](https://www.deeplearning.ai/short-courses/a2a-the-agent2agent-protocol/) | Короткий курс: несколько агентов обмениваются задачами по A2A |

## Изоляция, политики и наблюдаемость

| Материал | Зачем |
| --- | --- |
| [Kubernetes. Multi-tenancy](https://kubernetes.io/docs/concepts/security/multi-tenancy/) | Разделение ресурсов и доступов между командами |
| [kubernetes-sigs/agent-sandbox](https://github.com/kubernetes-sigs/agent-sandbox) | Изолированные окружения для агентов в Kubernetes |
| [CKAD](https://www.cncf.io/training/certification/ckad/) и [CKS](https://www.cncf.io/training/certification/cks/) | Kubernetes для приложений и безопасность кластера |
| [Open Policy Agent](https://www.openpolicyagent.org/docs/latest/) | Политики как код |
| [OpenTelemetry. Gen AI semantic conventions](https://opentelemetry.io/docs/specs/semconv/gen-ai/) | Метрики, логи, трассировки и соглашения для действий агентов |
| [OWASP GenAI. Agentic AI — Threats and Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/) | Угрозы агентных систем и меры защиты. Требования пишет Security, механизмы — эта роль |

## Надёжность и платформа как продукт

| Материал | Зачем |
| --- | --- |
| [Google. Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) и [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) | Надёжность, наблюдаемость, инциденты, безопасный выпуск. Русское издание — в разделе выше |
| Michael Nygard. Release It! | Устойчивость к сбоям, в том числе circuit breaker. [Второе издание](https://pragprog.com/titles/mnee2/release-it-second-edition/). Русский перевод первого издания — в разделе выше |
| Martin Kleppmann. Designing Data-Intensive Applications | Состояние, распределённые системы, повторы и согласованность. Русское второе издание, уже с Крисом Риккомини, — в разделе выше |
| [Temporal. Learn](https://learn.temporal.io/) | Практикумы по работам, которые переживают сбой и продолжаются |
| [CNCF. Platforms White Paper](https://tag-app-delivery.cncf.io/whitepapers/platforms/) | Что такое внутренняя платформа и как измерять её успех |
| Camille Fournier, Ian Nowland. Platform Engineering. O'Reilly, 2024 | Внутренняя платформа как продукт |
| Matthew Skelton, Manuel Pais. Team Topologies. [teamtopologies.com](https://teamtopologies.com/) | Как платформенная команда обслуживает продуктовые команды. Русская страница второго издания — в разделе выше |

## Изоляция сессии на кластере

| Материал | Зачем |
| --- | --- |
| [Kubernetes. Pod Security Admission](https://kubernetes.io/docs/concepts/security/pod-security-admission/) | Профиль ограничений до запуска. Тот же приём, что профиль песочницы до первого действия |
| [Kubernetes. Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/) | Сетевая граница сессии: куда ей можно ходить |
| [Kubernetes. Resource Quotas](https://kubernetes.io/docs/concepts/policy/resource-quotas/) | Лимит ресурсов на пространство имён, чтобы одна сессия не съела чужие |
| [OPA Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/) | Политика OPA на допуске объектов в кластер. Имя инструмента не требование роли |

## След, который нельзя подменить, и неопределённый результат

| Материал | Зачем |
| --- | --- |
| [Google. Building Secure and Reliable Systems](https://sre.google/books/building-secure-reliable-systems/) | Безопасность и надёжность как одно проектирование: нет проверки — нет действия |
| [SRE. Addressing Cascading Failures](https://sre.google/sre-book/addressing-cascading-failures/) | Как сбой одной сессии не снимает гарантии с остальных |
| [SRE. Handling Overload](https://sre.google/sre-book/handling-overload/) | Нагрузка, отказ в приёме работы и деградация без обрушения всей среды |
| [SRE. Postmortem Culture](https://sre.google/sre-book/postmortem-culture/) | Разбор без поиска виноватого: виден ход, а не человек |
| [Martin Fowler. CircuitBreaker](https://martinfowler.com/bliki/CircuitBreaker.html) | Автоматический останов серии сбоев. Короткое определение, не реализация |
| [Stripe. Idempotent requests](https://stripe.com/blog/idempotency) | Ключ повтора, чтобы внешнее действие не выполнилось дважды |
| [Google AIP-155. Request identification](https://google.aip.dev/155) | Тот же приём в проектировании API: повтор запроса не создаёт второй эффект |
| [Temporal. Understanding Temporal](https://docs.temporal.io/evaluate/understanding-temporal) | Длинная работа, которая продолжается после падения процесса |
| [W3C Trace Context](https://www.w3.org/TR/trace-context/) | Как связать передачу задачи, вызов инструмента и проверку в одну историю |

## Каталог инструментов, обмен и требования Security

| Материал | Зачем |
| --- | --- |
| [MCP. Security best practices, ревизия 2025-11-25](https://modelcontextprotocol.io/docs/2025-11-25/tutorials/security/security_best_practices) | Официальные риски MCP: права, согласие на вызов, токены, изоляция сервера. Перед опорой сверить номер ревизии на modelcontextprotocol.io |
| [OWASP. MCP Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html) | Минимальные права инструмента, песочница сервера, запрет молчаливого одобрения вызова |
| [A2A. Enterprise ready](https://a2a-protocol.org/latest/topics/enterprise-ready/) | TLS, идентичность, трассировка и аудит обмена между агентами. Правило компании жёстче: мимо брокера этап не передают |
| [OWASP. LLM Top 10](https://genai.owasp.org/llm-top-10/) | Подмена инструкций через внешние данные. Требования формулирует Security, механизмы делает эта роль |
| [NIST. AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | Общий язык с Security. Текст политики по нему пишет не эта роль |
| [SPIFFE](https://www.spiffe.io/docs/latest/spiffe-about/overview/) | Идентичность рабочей нагрузки. Нужна, чтобы в журнале был субъект, а не только имя пода |
| [SLSA](https://slsa.dev/spec/latest/) | Ближайший зрелый аналог комплекта доказательств в поставке. Это не стандарт комплекта доказательств агентной задачи: его порог задаёт Eval |
| [Sigstore](https://docs.sigstore.dev/) | Подпись артефакта, которую нельзя тихо подменить. Рядом со SLSA, для выпуска объектов среды |

## Платформа как продукт для нескольких команд

| Материал | Зачем |
| --- | --- |
| [CNCF. Platform Engineering Maturity Model](https://tag-app-delivery.cncf.io/whitepapers/platform-eng-maturity-model/) | Пять сторон зрелости внутренней платформы. Высший уровень не цель сам по себе: модель прямо просит не гнаться за ним без нужды |

## Учебный проект

Два агента передают друг другу задачу через платформу, используют один внешний инструмент и продолжают работу после искусственного сбоя. В проекте должны быть проверка прав до действия, история действий, ограничение расходов и обработка случая, когда внешний сервис выполнил операцию, но ответ потерялся.
