# Теория оптимизации

## Основы оптимизации
- Постановка задачи оптимизации [→](/notes/optimization_problem.md)
- Классификация задач оптимизации [→](/notes/optimization_classification.md)
- Условия оптимальности [→](/notes/optimality_conditions.md)
- Методы поиска экстремума [→](/notes/extremum_search.md)
- Численные методы оптимизации [→](/notes/numerical_optimization.md)
- Выпуклость и вогнутость функций [→](/notes/convexity.md)
- Локальные и глобальные экстремумы [→](/notes/local_global_extrema.md)
- Необходимые и достаточные условия [→](/notes/optimality_conditions_advanced.md)
- Теорема Куна-Таккера [→](/notes/kkt_conditions.md)
- Седловые точки [→](/notes/saddle_points.md)

## Линейное программирование
### Основные концепции
- Формы записи задач ЛП [→](/notes/lp_forms.md)
- Геометрическая интерпретация [→](/notes/lp_geometry.md)
- Базисные решения [→](/notes/basic_solutions.md)
- Двойственность [→](/notes/lp_duality.md)
- Теорема о дополняющей нежесткости [→](/notes/complementary_slackness.md)
- Экономическая интерпретация [→](/notes/lp_economics.md)
- Анализ чувствительности [→](/notes/sensitivity_analysis.md)
- Вырожденность в ЛП [→](/notes/lp_degeneracy.md)
- Целочисленное ЛП [→](/notes/integer_lp.md)

### Методы решения
- Симплекс-метод [→](/notes/simplex_method.md)
- Метод искусственного базиса [→](/notes/artificial_basis.md)
- Метод внутренней точки [→](/notes/interior_point.md)
- Метод эллипсоидов [→](/notes/ellipsoid_method.md)
- Двухфазный симплекс-метод [→](/notes/two_phase_simplex.md)
- Модифицированный симплекс-метод [→](/notes/modified_simplex.md)
- Параметрическое ЛП [→](/notes/parametric_lp.md)
- Декомпозиция Данцига-Вульфа [→](/notes/dantzig_wolfe.md)
- Метод генерации столбцов [→](/notes/column_generation_lp.md)

### Специальные задачи
- Транспортная задача [→](/notes/transportation_problem.md)
- Задача о назначениях [→](/notes/assignment_problem.md)
- Задача о потоках [→](/notes/flow_problem.md)
- Задача о максимальном потоке [→](/notes/max_flow.md)
- Задача о минимальном разрезе [→](/notes/min_cut.md)
- Задача о кратчайшем пути [→](/notes/shortest_path.md)
- Многопродуктовая транспортная задача [→](/notes/multicommodity_flow.md)
- Задача о паросочетаниях [→](/notes/matching_problem.md)
- Задача коммивояжера [→](/notes/traveling_salesman.md)

## Нелинейная оптимизация
### Безусловная оптимизация
- Градиентные методы [→](/notes/gradient_methods.md)
- Метод Ньютона [→](/notes/newton_optimization.md)
- Квазиньютоновские методы [→](/notes/quasi_newton.md)
- Метод сопряженных градиентов [→](/notes/conjugate_gradient_optimization.md)
- Метод наискорейшего спуска [→](/notes/steepest_descent_opt.md)
- Метод Флетчера-Ривса [→](/notes/fletcher_reeves.md)
- Метод Полака-Рибьера [→](/notes/polak_ribiere.md)
- Метод Бройдена-Флетчера-Гольдфарба-Шанно [→](/notes/bfgs.md)
- Метод Пауэлла [→](/notes/powell_method.md)
- Метод Нелдера-Мида [→](/notes/nelder_mead.md)

### Условная оптимизация
- Метод множителей Лагранжа [→](/notes/lagrange_multipliers.md)
- Метод штрафных функций [→](/notes/penalty_methods.md)
- Метод барьерных функций [→](/notes/barrier_methods.md)
- Метод доверительной области [→](/notes/trust_region.md)
- Метод проекции градиента [→](/notes/gradient_projection.md)
- Метод последовательного квадратичного программирования [→](/notes/sqp.md)
- Метод внутренней точки для нелинейной оптимизации [→](/notes/nonlinear_interior_point.md)
- Метод активного множества [→](/notes/active_set.md)
- Метод расширенного лагранжиана [→](/notes/augmented_lagrangian.md)

## Выпуклая оптимизация
### Теоретические основы
- Выпуклые множества [→](/notes/convex_sets.md)
- Выпуклые функции [→](/notes/convex_functions.md)
- Субградиенты [→](/notes/subgradients.md)
- Двойственность [→](/notes/convex_duality.md)
- Сильная выпуклость [→](/notes/strong_convexity.md)
- Условия оптимальности [→](/notes/optimality_conditions.md)
- Теорема Каруша-Куна-Таккера [→](/notes/kkt_conditions.md)
- Барьерные функции [→](/notes/barrier_functions.md)
- Сопряженные функции [→](/notes/conjugate_functions.md)
- Теорема Фенхеля-Рокафеллара [→](/notes/fenchel_rockafellar.md)

### Методы решения
- Метод центров [→](/notes/center_method.md)
- Метод отсечений [→](/notes/cutting_plane.md)
- Субградиентные методы [→](/notes/subgradient_methods.md)
- Проксимальные методы [→](/notes/proximal_methods.md)
- Метод эллипсоидов [→](/notes/ellipsoid_method_convex.md)
- Метод зеркального спуска [→](/notes/mirror_descent.md)
- Метод внутренней точки [→](/notes/interior_point_convex.md)
- Метод пучка [→](/notes/bundle_method.md)
- Метод сглаживания [→](/notes/smoothing_method.md)
- Ускоренные градиентные методы [→](/notes/accelerated_gradient.md)

## Целочисленное программирование
### Точные методы
- Метод ветвей и границ [→](/notes/branch_and_bound.md)
- Метод отсечения Гомори [→](/notes/gomory_cuts.md)
- Метод ветвей и отсечений [→](/notes/branch_and_cut.md)
- Метод ветвей и цен [→](/notes/branch_and_price.md)
- Метод динамического программирования [→](/notes/dynamic_programming_ip.md)
- Метод перебора с возвратом [→](/notes/backtracking.md)
- Метод Лэнд-Дойг [→](/notes/land_doig.md)
- Метод Бендерса [→](/notes/benders_decomposition.md)
- Метод Данцига-Вульфа [→](/notes/dantzig_wolfe_ip.md)
- Метод лагранжевой релаксации [→](/notes/lagrangian_relaxation.md)

### Эвристические методы
- Локальный поиск [→](/notes/local_search.md)
- Метод генерации столбцов [→](/notes/column_generation.md)
- Релаксационные методы [→](/notes/relaxation_methods.md)
- Жадные алгоритмы [→](/notes/greedy_algorithms.md)
- Метод переменных окрестностей [→](/notes/variable_neighborhood_ip.md)
- Метод случайного спуска [→](/notes/random_descent.md)
- Поиск с запретами [→](/notes/tabu_search_ip.md)
- Имитация отжига [→](/notes/simulated_annealing_ip.md)
- Генетические алгоритмы для ЦП [→](/notes/genetic_algorithms_ip.md)
- Муравьиные алгоритмы для ЦП [→](/notes/ant_colony_ip.md)

## Динамическое программирование
### Основные концепции
- Принцип оптимальности Беллмана [→](/notes/bellman_principle.md)
- Рекуррентные соотношения [→](/notes/recurrence_relations.md)
- Функция Беллмана [→](/notes/bellman_function.md)
- Уравнение Беллмана [→](/notes/bellman_equation.md)
- Принцип вложения [→](/notes/embedding_principle.md)
- Условная оптимизация [→](/notes/conditional_optimization.md)
- Марковские процессы принятия решений [→](/notes/markov_decision.md)
- Стохастическое динамическое программирование [→](/notes/stochastic_dp_basics.md)
- Адаптивное динамическое программирование [→](/notes/adaptive_dp.md)
- Приближенное динамическое программирование [→](/notes/approximate_dp_basics.md)

### Классические задачи
- Задача о рюкзаке [→](/notes/knapsack_problem.md)
- Задача о кратчайшем пути [→](/notes/shortest_path_dp.md)
- Задача о расписании [→](/notes/scheduling_dp.md)
- Задача о разбиении множества [→](/notes/set_partitioning.md)
- Задача о матричном умножении [→](/notes/matrix_chain.md)
- Задача о редактировании строк [→](/notes/string_edit.md)
- Задача о наибольшей общей подпоследовательности [→](/notes/longest_common_subsequence.md)
- Задача о разбиении числа [→](/notes/number_partitioning.md)
- Задача об оптимальном бинарном дереве поиска [→](/notes/optimal_bst.md)
- Задача о максимальном потоке минимальной стоимости [→](/notes/min_cost_flow_dp.md)

### Продвинутые методы
- Стохастическое ДП [→](/notes/stochastic_dp.md)
- Приближенное ДП [→](/notes/approximate_dp.md)
- Нейродинамическое программирование [→](/notes/neuro_dp.md)
- Q-обучение [→](/notes/q_learning.md)
- SARSA [→](/notes/sarsa.md)
- Актор-критик методы [→](/notes/actor_critic.md)
- Темпоральные разности [→](/notes/temporal_difference.md)
- Глубокое Q-обучение [→](/notes/deep_q_learning.md)
- Политочные градиенты [→](/notes/policy_gradients.md)
- Иерархическое ДП [→](/notes/hierarchical_dp.md)

## Стохастическая оптимизация
### Градиентные методы
- Стохастический градиентный спуск [→](/notes/sgd.md)
- Адаптивные методы [→](/notes/adaptive_methods.md)
- Методы моментов [→](/notes/momentum_methods.md)
- Adam [→](/notes/adam.md)
- RMSprop [→](/notes/rmsprop.md)
- AdaGrad [→](/notes/adagrad.md)
- AdaDelta [→](/notes/adadelta.md)
- Nadam [→](/notes/nadam.md)
- AMSGrad [→](/notes/amsgrad.md)
- FTRL [→](/notes/ftrl.md)

### Эволюционные методы
- Генетические алгоритмы [→](/notes/genetic_algorithms_opt.md)
- Эволюционные стратегии [→](/notes/evolution_strategies.md)
- Дифференциальная эволюция [→](/notes/differential_evolution_opt.md)
- Коэволюция [→](/notes/coevolution.md)
- Островные модели [→](/notes/island_models.md)
- Мультипопуляционные методы [→](/notes/multipopulation.md)
- Меметические алгоритмы [→](/notes/memetic_algorithms.md)
- Самоадаптивные методы [→](/notes/self_adaptive.md)
- Гибридные эволюционные алгоритмы [→](/notes/hybrid_evolutionary.md)
- Параллельные эволюционные алгоритмы [→](/notes/parallel_evolutionary.md)

### Другие подходы
- Байесовская оптимизация [→](/notes/bayesian_optimization.md)
- Метод имитации отжига [→](/notes/simulated_annealing_opt.md)
- Метод Монте-Карло [→](/notes/monte_carlo_opt.md)
- Метод перекрестной энтропии [→](/notes/cross_entropy.md)
- Квантовая оптимизация [→](/notes/quantum_optimization.md)
- Метод роя частиц [→](/notes/particle_swarm.md)
- Гауссовские процессы [→](/notes/gaussian_processes.md)
- Метод последовательного планирования [→](/notes/sequential_planning.md)
- Адаптивное случайное поведение [→](/notes/adaptive_random.md)
- Метод распространения вероятностей [→](/notes/probability_propagation.md)

## Многокритериальная оптимизация
### Теоретические основы
- Парето-оптимальность [→](/notes/pareto_optimality.md)
- Доминирование решений [→](/notes/solution_dominance.md)
- Фронт Парето [→](/notes/pareto_front.md)
- Векторная оптимизация [→](/notes/vector_optimization.md)
- Скаляризация критериев [→](/notes/criteria_scalarization.md)
- Лексикографическая оптимизация [→](/notes/lexicographic_optimization.md)
- Компромиссный анализ [→](/notes/trade_off_analysis.md)
- Теория полезности [→](/notes/utility_theory.md)
- Интерактивные методы [→](/notes/interactive_methods.md)
- Робастная оптимизация [→](/notes/robust_optimization.md)

### Методы решения
- Метод взвешенных сумм [→](/notes/weighted_sum.md)
- Метод ε-ограничений [→](/notes/epsilon_constraint.md)
- Метод достижения цели [→](/notes/goal_programming.md)
- Метод идеальной точки [→](/notes/ideal_point.md)
- Метод компромиссного программирования [→](/notes/compromise_programming.md)
- Метод последовательной оптимизации [→](/notes/sequential_optimization.md)
- Метод нормальной границы [→](/notes/normal_boundary.md)
- Метод физического программирования [→](/notes/physical_programming.md)
- Метод равномерной оптимизации [→](/notes/uniform_optimization.md)
- Метод глобального критерия [→](/notes/global_criterion.md)

### Эволюционные подходы
- Алгоритм NSGA-II [→](/notes/nsga2.md)
- Алгоритм MOEA/D [→](/notes/moead.md)
- Многоцелевые ГА [→](/notes/multi_objective_ga.md)
- SPEA2 [→](/notes/spea2.md)
- PESA-II [→](/notes/pesa2.md)
- SMS-EMOA [→](/notes/sms_emoa.md)
- IBEA [→](/notes/ibea.md)
- HypE [→](/notes/hype.md)
- R-NSGA-II [→](/notes/r_nsga2.md)
- MO-CMA-ES [→](/notes/mo_cma_es.md)

## Метаэвристические алгоритмы
### Траекторные методы
- Поиск с запретами [→](/notes/tabu_search.md)
- Переменный поиск окрестностей [→](/notes/variable_neighborhood.md)
- Локальный поиск со случайными блужданиями [→](/notes/random_walk.md)
- Итерированный локальный поиск [→](/notes/iterated_local_search.md)
- Поиск с возвратом [→](/notes/backtracking_search.md)
- Метод направленного случайного поиска [→](/notes/guided_random_search.md)
- Метод восхождения на холм [→](/notes/hill_climbing.md)
- Метод имитации отжига [→](/notes/simulated_annealing_meta.md)
- Поиск в большой окрестности [→](/notes/large_neighborhood.md)
- Гармонический поиск [→](/notes/harmony_search.md)

### Популяционные методы
- Муравьиные алгоритмы [→](/notes/ant_colony_opt.md)
- Алгоритм роя частиц [→](/notes/particle_swarm_opt.md)
- Алгоритм пчелиного роя [→](/notes/bee_colony_opt.md)
- Искусственные иммунные системы [→](/notes/artificial_immune.md)
- Светлячковый алгоритм [→](/notes/firefly_algorithm.md)
- Алгоритм кукушки [→](/notes/cuckoo_search.md)
- Алгоритм летучих мышей [→](/notes/bat_algorithm.md)
- Алгоритм волчьей стаи [→](/notes/wolf_pack.md)
- Алгоритм китов [→](/notes/whale_optimization.md)
- Алгоритм серых волков [→](/notes/grey_wolf.md)
