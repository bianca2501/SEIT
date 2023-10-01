% Create a knowledge base
knowledge_base1([
    % Facts
    fact1(the_sky_is_blue),
    fact2(the_grass_is_green),
    fact3(the_sun_is_a_star),
    % Rules
    rule1(if(raining, then(the_ground_is_wet))),
    rule2(if(eat_too_much, then(get_sick))),
    rule3(if(study_hard, then(get_good_grades)))
]).
% Append facts
append_facts(knowledge_base1, [
    fact4(the_moon_is_a_satellite),
    fact5(the_earth_is_a_planet)
]).
% Append rules
append_rules(knowledge_base1, [
    rule4(if(the_sun_is_shining, then(the_day_is_bright))),
    rule5(if(the_temperature_is_below_freezing, then(the_water_is_frozen)))
]).
% Delete facts
delete_facts(knowledge_base1, [
    fact2(the_grass_is_green),
    fact3(the_sun_is_a_star)
]).
% Delete rule
delete_rule(knowledge_base1, rule1(if(raining, then(the_ground_is_wet)))).
% Append facts at the beginning and end of knowledge base
append_facts_at_beginning_and_end(knowledge_base1, [
    fact0(the_universe_is_vast),
    fact6(the_future_is_uncertain)
]).