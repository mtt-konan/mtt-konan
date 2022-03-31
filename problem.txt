2022-03-31 11:46:09 INFO [models.settings]: 设置CONFIG: single_mode_target_training_levels: {} -> {1: 5, 2: 3, 3: 3, 4: 0, 5: 1}
2022-03-31 11:46:09 INFO [__main__]: Server started: 127.0.0.1:12780
['afk.py', 'auto_crane.py', 'avoid_high_failure_rate_trains.py', 'less_op.py', 'limited_sale_buy_everything.py', 'limited_sale_buy_first_3.py', 'limited_sale_ignore.py', 'more_g1.py', 'no_event_prompt.py', 'no_ocr_prompt.py', 'pause_before_command.py', 'pause_before_race_continue.py', 'SSR樫本理子.py', 'SSR駿川たづな.py', 'use_legacy_screenshot.py']
2022-03-31 11:46:32 INFO [api.mission]: Start Success
2022-03-31 11:46:32 INFO [auto_derby.window]: width=540 height=960
2022-03-31 11:46:32 INFO [auto_derby.window]: already in wanted size
2022-03-31 11:46:33 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_command_training.png>, pos=(199, 760), similarity=0.97
2022-03-31 11:46:33 INFO [auto_derby.scenes.scene]: enter: single-mode-command
2022-03-31 11:46:33 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_command_training.png>, pos=(199, 760), similarity=0.97
2022-03-31 11:46:33 INFO [auto_derby.scenes.scene]: entered: single-mode-command
2022-03-31 11:46:33 INFO [auto_derby.window]: width=540 height=960
2022-03-31 11:46:33 INFO [auto_derby.window]: already in wanted size
2022-03-31 11:46:33 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_aoharu_class_detail_button.png>, pos=(126, 591), similarity=0.98
2022-03-31 11:46:33 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
Matching current displaying image: value=,, similarity=0.742.
Is this correct? (Y/N)y
2022-03-31 11:46:47 INFO [auto_derby.ocr]: labeled: hash=0000000000000000000000000000000000000000ff03ff1fff1fff1fff0fff07, value=,
2022-03-31 11:46:48 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:49 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:50 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:52 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:53 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:54 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:55 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:56 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:57 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
2022-03-31 11:46:58 INFO [auto_derby.template]: match: tmpl=tmpl<single_mode_character_detail_button.png>, pos=(466, 559), similarity=0.95
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
