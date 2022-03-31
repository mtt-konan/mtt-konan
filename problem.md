2022-03-29 01:54:20 INFO [models.settings]: 设置CONFIG: single_mode_target_training_levels: {} -> {1: 5, 2: 3, 3: 3, 4: 0, 5: 1}
2022-03-29 01:54:20 INFO [__main__]: Server started: 127.0.0.1:12780
['afk.py', 'auto_crane.py', 'avoid_high_failure_rate_trains.py', 'less_op.py', 'limited_sale_buy_everything.py', 'limited_sale_buy_first_3.py', 'limited_sale_ignore.py', 'more_g1.py', 'no_event_prompt.py', 'no_ocr_prompt.py', 'pause_before_command.py', 'pause_before_race_continue.py', 'SSR樫本理子.py', 'SSR駿川たづな.py', 'use_legacy_screenshot.py']
2022-03-29 01:54:30 INFO [api.mission]: Start Success
2022-03-29 01:54:30 INFO [auto_derby.plugin]: installed: no_ocr_prompt
2022-03-29 01:54:30 INFO [auto_derby.plugin]: installed: no_event_prompt
2022-03-29 01:54:30 INFO [auto_derby.plugin]: installed: auto_crane
2022-03-29 01:54:30 INFO [auto_derby.plugin]: installed: afk
2022-03-29 01:54:30 INFO [auto_derby.window]: width=540 height=960
2022-03-29 01:54:30 INFO [auto_derby.window]: already in wanted size
2022-03-29 01:19:52 INFO [auto_derby.window]: width=540 height=960
2022-03-29 01:19:52 INFO [auto_derby.window]: already in wanted size
2022-03-29 01:19:52 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_aoharu_class_detail_button.png>, pos=(126, 591), similarity=0.98
2022-03-29 01:19:52 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:52 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:54 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:54 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:55 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:55 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:56 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:56 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:57 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:57 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:58 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:58 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:19:59 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:19:59 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:20:00 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:20:00 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:20:01 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:20:01 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:20:02 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:20:02 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
2022-03-29 01:20:04 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-29 01:20:04 WARNING [auto_derby.ocr]: using low similarity label: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,, similarity=0.7421875
Exception in thread Thread-4:
Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "threading.py", line 932, in _bootstrap_inner
  File "threading.py", line 870, in run
  File "auto_derby\okderby.py", line 62, in start
  File "auto_derby\jobs\nurturing.py", line 229, in nurturing
  File "auto_derby\jobs\nurturing.py", line 90, in _ac_handle_turn
  File "auto_derby\jobs\nurturing.py", line 43, in _handle_turn
  File "auto_derby\scenes\single_mode\command.py", line 93, in recognize
  File "auto_derby\action.py", line 84, in run_with_retry
  File "auto_derby\action.py", line 84, in run_with_retry
  File "auto_derby\action.py", line 84, in run_with_retry
  [Previous line repeated 7 more times]
  File "auto_derby\action.py", line 79, in run_with_retry
  File "auto_derby\scenes\single_mode\command.py", line 94, in <lambda>
  File "auto_derby\single_mode\context.py", line 316, in update_by_command_scene
  File "auto_derby\single_mode\context.py", line 57, in _ocr_date
ValueError: substring not found