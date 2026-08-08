# Graph Report - .  (2026-08-08)

## Corpus Check
- Large corpus: 440 files · ~1,415,876 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 15815 nodes · 61988 edges · 343 communities (299 shown, 44 thin omitted)
- Extraction: 74% EXTRACTED · 26% INFERRED · 0% AMBIGUOUS · INFERRED: 16025 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- C++ Hybrid LSP tests
- Rust LSP resolution tests
- Agent registry & profiles
- MCP command executors
- Install & agent config upsert
- PHP LSP resolution tests
- MCP JSON-RPC server
- Java LSP coverage tests
- Daemon IPC & sockets
- Language detection & extensions
- Store types & architecture info
- TypeScript LSP resolution tests
- Compile-commands parsing
- Graph buffer dump (CBMDump)
- Daemon runtime IPC frames
- Hash table & graph buffer utils
- Daemon runtime workers & progress
- File discovery & gitignore
- Daemon application jobs
- Cypher query engine
- Daemon update worker
- Daemon IPC startup lock
- C Hybrid LSP resolution
- JSON-like config editor
- Regression repro tests
- Graph buffer traversal & parallelism
- Activation transaction (install)
- Pipeline lifecycle & store
- Rust closure resolution
- YAML config editor
- Grammar build tests
- Registry & type resolution
- Project lock registry
- Search output & impact analysis
- Daemon maintenance & version cohort
- Arena memory & shared registries
- Diagnostics & logging
- FQN & relative import resolution
- Language definition extractors
- Agent client probes & adapters
- Subprocess management
- Java LSP resolution tests
- LSP resolution probe tests
- Watcher auto-sync
- Daemon conflicts & SHA-256
- Parallel extraction workers
- CLI main & hook admission
- Multi-language extraction tests
- Path utils & profiling
- Kotlin LSP resolution tests
- Private file locks (Windows)
- Python LSP resolution tests
- Incremental update & ADR tools
- Node creation probes
- ADR management & Louvain
- Community 55
- Community 56
- Community 57
- Community 58
- Community 59
- Community 60
- Community 61
- Community 62
- Community 63
- Community 64
- Community 65
- Community 66
- Community 67
- Community 68
- Community 69
- Community 70
- Community 71
- Community 72
- Community 73
- Community 74
- Community 75
- Community 76
- Community 77
- Community 78
- Community 79
- Community 80
- Community 81
- Community 82
- Community 83
- Community 84
- Community 85
- Community 86
- Community 87
- Community 88
- Community 89
- Community 90
- Community 91
- Community 92
- Community 93
- Community 94
- Community 95
- Community 96
- Community 97
- Community 98
- Community 99
- Community 100
- Community 101
- Community 102
- Community 103
- Community 104
- Community 105
- Community 106
- Community 107
- Community 108
- Community 109
- Community 110
- Community 111
- Community 112
- Community 113
- Community 114
- Community 115
- Community 116
- Community 117
- Community 118
- Community 119
- Community 120
- Community 121
- Community 122
- Community 123
- Community 124
- Community 125
- Community 126
- Community 127
- Community 128
- Community 129
- Community 130
- Community 131
- Community 132
- Community 133
- Community 134
- Community 135
- Community 136
- Community 137
- Community 138
- Community 139
- Community 140
- Community 141
- Community 142
- Community 143
- Community 144
- Community 145
- Community 146
- Community 147
- Community 148
- Community 149
- Community 150
- Community 151
- Community 152
- Community 153
- Community 154
- Community 155
- Community 156
- Community 157
- Community 158
- Community 159
- Community 160
- Community 161
- Community 162
- Community 163
- Community 164
- Community 165
- Community 166
- Community 167
- Community 168
- Community 169
- Community 170
- Community 171
- Community 172
- Community 173
- Community 174
- Community 175
- Community 176
- Community 177
- Community 178
- Community 179
- Community 180
- Community 181
- Community 182
- Community 183
- Community 184
- Community 185
- Community 186
- Community 187
- Community 188
- Community 189
- Community 190
- Community 191
- Community 192
- Community 193
- Community 194
- Community 195
- Community 196
- Community 197
- Community 198
- Community 199
- Community 200
- Community 201
- Community 202
- Community 203
- Community 204
- Community 205
- Community 206
- Community 207
- Community 208
- Community 209
- Community 210
- Community 211
- Community 212
- Community 213
- Community 214
- Community 215
- Community 216
- Community 217
- Community 218
- Community 219
- Community 220
- Community 221
- Community 222
- Community 223
- Community 224
- Community 225
- Community 226
- Community 227
- Community 228
- Community 229
- Community 230
- Community 231
- Community 232
- Community 233
- Community 234
- Community 235
- Community 236
- Community 237
- Community 238
- Community 239
- Community 240
- Community 241
- Community 242
- Community 243
- Community 244
- Community 245
- Community 246
- Community 247
- Community 248
- Community 249
- Community 250
- Community 251
- Community 252
- Community 253
- Community 254
- Community 255
- Community 256
- Community 257
- Community 259
- Community 260
- Community 261
- Community 262
- Community 263
- Community 264
- Community 265
- Community 266
- Community 267
- Community 268
- Community 269
- Community 270
- Community 271
- Community 272
- Community 273
- Community 274
- Community 275
- Community 276
- Community 278
- Community 279
- Community 280
- Community 281
- Community 282
- Community 283
- Community 284
- Community 285
- Community 286
- Community 287
- Community 288
- Community 289
- Community 290
- Community 291
- Community 292
- Community 293
- Community 294
- Community 295
- Community 296
- Community 297
- Community 298
- Community 299
- Community 300
- Community 301
- Community 302
- Community 303
- Community 304
- Community 305
- Community 306
- Community 307
- Community 308
- Community 309
- Community 310
- Community 311
- Community 312
- Community 313

## God Nodes (most connected - your core abstractions)
1. `find_resolved()` - 679 edges
2. `extract_cpp()` - 609 edges
3. `cbm_store_close()` - 568 edges
4. `cbm_mkdtemp()` - 522 edges
5. `extract_rust()` - 498 edges
6. `extract_php()` - 284 edges
7. `cov_extract()` - 282 edges
8. `require_resolved()` - 274 edges
9. `cbm_setenv()` - 271 edges
10. `extract_ts()` - 264 edges

## Surprising Connections (you probably didn't know these)
- `index_supervisor_test_capture_log()` --calls--> `cbm_progress_sink_fn()`  [INFERRED]
  tests/test_index_supervisor.c → src/cli/progress_sink.c
- `cypher_exec_deadline_aborts_runaway_query_issue601()` --calls--> `cbm_cypher_test_set_deadline_ms()`  [INFERRED]
  tests/test_cypher.c → src/cypher/cypher.c
- `daemon_application_thread_start_failure_rolls_back_job_reservation()` --calls--> `cbm_daemon_application_fail_next_job_thread_start_for_test()`  [INFERRED]
  tests/test_daemon_application.c → src/daemon/application.c
- `daemon_application_queues_explicit_index_behind_physical_job_limit()` --calls--> `cbm_daemon_application_busy_queue_waits_for_test()`  [INFERRED]
  tests/test_daemon_application.c → src/daemon/application.c
- `daemon_application_cancel_before_worker_start_skips_worker()` --calls--> `cbm_daemon_application_hold_job_before_start_for_test()`  [INFERRED]
  tests/test_daemon_application.c → src/daemon/application.c

## Import Cycles
- None detected.

## Communities (343 total, 44 thin omitted)

### Community 0 - "C++ Hybrid LSP tests"
Cohesion: 0.01
Nodes (601): TEST, clsp_abseil_status_or(), clsp_adl_no_false_positive(), clsp_adl_operator_free_func(), clsp_adl_std_sort(), clsp_adl_swap(), clsp_algorithm_with_lambda(), clsp_audit_cpp_aggregate_init() (+593 more)

### Community 1 - "Rust LSP resolution tests"
Cohesion: 0.02
Nodes (353): extract_rust(), require_resolved(), rustlsp_box_constructor(), rustlsp_chained_method_calls(), rustlsp_cov_async_await_chain(), rustlsp_cov_async_block(), rustlsp_cov_async_fn_decl(), rustlsp_cov_async_join_call() (+345 more)

### Community 2 - "Agent registry & profiles"
Cohesion: 0.02
Nodes (285): cbm_agent_registry_context_t, cbm_detected_agents_t, cbm_hook_json_prewrite_test_hook_t, cbm_json_mcp_schema_t, cbm_tiered_profile_set_t, hooks_remove_args_t, hooks_upsert_args_t, mcp_uninstall_args_t (+277 more)

### Community 3 - "MCP command executors"
Cohesion: 0.03
Nodes (266): cbm_mcp_command_test_hook_fn, cbm_mcp_index_executor_fn, cbm_project_t, coverage_path_result_t, grep_match_t, scc_graph_t, search_result_t, application_job_failure_response() (+258 more)

### Community 4 - "Install & agent config upsert"
Cohesion: 0.05
Nodes (238): cbm_build_install_plan_json(), cbm_detect_shell_rc(), cbm_ensure_path(), cbm_install_agent_configs(), cbm_install_editor_mcp(), cbm_install_editor_mcp_with_previous_for_testing(), cbm_install_openclaw_mcp(), cbm_install_zed_mcp() (+230 more)

### Community 5 - "PHP LSP resolution tests"
Cohesion: 0.03
Nodes (223): TEST, extract_php(), find_resolved(), phplsp_aliased_static_chain(), phplsp_anonymous_class(), phplsp_array_object_iterator(), phplsp_array_shape_call_no_crash(), phplsp_at_method_then_real() (+215 more)

### Community 6 - "MCP JSON-RPC server"
Cohesion: 0.04
Nodes (213): cbm_jsonrpc_response_t, mcp_test_env_backup_t, cbm_jsonrpc_format_error(), cbm_jsonrpc_format_response(), cbm_mcp_get_arguments(), cbm_mcp_get_tool_name(), cbm_mcp_server_evict_idle(), cbm_mcp_server_free() (+205 more)

### Community 7 - "Java LSP coverage tests"
Cohesion: 0.03
Nodes (204): TEST, cov_bind_final_local(), cov_bind_for_loop_init(), cov_bind_local_int(), cov_bind_multi_decl(), cov_bind_var_string(), cov_cast_arr_elem(), cov_cast_chained() (+196 more)

### Community 8 - "Daemon IPC & sockets"
Cohesion: 0.04
Nodes (192): cbm_daemon_ipc_listener_t, cbm_ipc_pending_ops_t, dev_t, ino_t, posix_record_state_t, posix_socket_identity_t, posix_socket_record_t, process_lock_entry_t (+184 more)

### Community 9 - "Language detection & extensions"
Cohesion: 0.03
Nodes (195): cbm_language_for_extension(), TEST, lang_ext_ada(), lang_ext_agda(), lang_ext_apex(), lang_ext_assembly(), lang_ext_astro(), lang_ext_awk() (+187 more)

### Community 10 - "Store types & architecture info"
Cohesion: 0.04
Nodes (186): cbm_architecture_info_t, cbm_cluster_info_t, cbm_cross_pkg_boundary_t, cbm_file_tree_entry_t, cbm_node_hop_t, cbm_package_summary_t, sqlite3_context, sqlite3_stmt (+178 more)

### Community 11 - "TypeScript LSP resolution tests"
Cohesion: 0.03
Nodes (180): TEST, extract_ts(), tslsp_abstract_concrete_dispatch(), tslsp_alias_simple(), tslsp_array_of_class_map(), tslsp_await_promise_all(), tslsp_callback_returning_method_call(), tslsp_chain_fluent() (+172 more)

### Community 12 - "Compile-commands parsing"
Cohesion: 0.03
Nodes (170): cbm_change_coupling_t, cbm_changed_file_t, cbm_commit_files_t, cbm_compile_flags_t, cbm_env_kv_t, NamedEdgePropertyObservation, yyjson_val, cbm_compile_flags_free() (+162 more)

### Community 13 - "Graph buffer dump (CBMDump)"
Cohesion: 0.05
Nodes (164): CBMDumpEdge, CBMDumpNode, CBMInfraBinding, edge_ptr_array_t, node_ptr_array_t, alloc_next_id(), build_dump_edges(), build_dump_nodes() (+156 more)

### Community 14 - "Daemon runtime IPC frames"
Cohesion: 0.05
Nodes (161): cbm_daemon_runtime_service_state_t, frontend_eof_fixture_t, PROCESS_INFORMATION, runtime_application_context_t, runtime_test_fixture_t, host_runtime_stop_free(), cbm_daemon_frame_type_t, cbm_daemon_ipc_connection_close() (+153 more)

### Community 15 - "Hash table & graph buffer utils"
Cohesion: 0.04
Nodes (153): cbm_edge_capture_t, cbm_gbuf_node_visitor_fn, cbm_ht_iter_fn, cbm_incremental_route_t, closure_plan_t, closure_resolve_t, semantic_manifest_builder_t, CBMHashTable (+145 more)

### Community 16 - "Daemon runtime workers & progress"
Cohesion: 0.04
Nodes (157): cbm_daemon_runtime_cancel_result_t, cbm_daemon_runtime_operation_t, cbm_daemon_runtime_service_config_t, cbm_daemon_runtime_worker_t, cbm_mutex_t, runtime_process_image_reference_t, runtime_windows_process_image_snapshot_t, cbm_progress_sink_fini() (+149 more)

### Community 17 - "File discovery & gitignore"
Cohesion: 0.05
Nodes (141): git_env_snapshot_t, cbm_index_mode_t, cbm_discover(), cbm_discover_free(), cbm_has_ignored_suffix(), cbm_matches_fast_pattern(), cbm_should_skip_dir(), cbm_should_skip_filename() (+133 more)

### Community 18 - "Daemon application jobs"
Cohesion: 0.04
Nodes (143): application_attempt_decision_t, application_attempt_status_t, application_attempt_t, application_job_execution_t, application_job_subscribe_status_t, cbm_daemon_application_job_t, cbm_daemon_application_session_t, cbm_daemon_application_watch_t (+135 more)

### Community 19 - "Cypher query engine"
Cohesion: 0.08
Nodes (135): cbm_cypher_result_t, cbm_cypher_execute(), cbm_cypher_result_free(), cbm_store_close(), cbm_cypher_result_t, cbm_store_t, TEST, cypher_apply_limit() (+127 more)

### Community 20 - "Daemon update worker"
Cohesion: 0.08
Nodes (133): app_env_backup_t, app_fake_update_context_t, app_fake_worker_context_t, app_project_lock_fixture_t, app_watch_race_fixture_t, cbm_daemon_application_config_t, cbm_daemon_application_update_ops_t, cbm_daemon_application_update_poll_t (+125 more)

### Community 21 - "Daemon IPC startup lock"
Cohesion: 0.08
Nodes (131): acl_tag_t, cbm_daemon_ipc_posix_publication_hook_fn, cbm_daemon_ipc_startup_gate_fn, ipc_pending_fake_t, ipc_test_startup_gate_t, ipc_test_win_env_t, cbm_daemon_ipc_startup_lock_t, cbm_daemon_ipc_endpoint_address() (+123 more)

### Community 22 - "C Hybrid LSP resolution"
Cohesion: 0.02
Nodes (133): clsp_audit_c_array_subscript_call(), clsp_audit_c_assert_macro_call(), clsp_audit_c_cast_then_field_call(), clsp_audit_c_comma_operator(), clsp_audit_c_for_loop_func_call(), clsp_audit_c_func_ptr_alias(), clsp_audit_c_generic_selection(), clsp_audit_c_nested_struct_field_call() (+125 more)

### Community 23 - "JSON-like config editor"
Cohesion: 0.06
Nodes (130): cbm_json_like_precommit_test_hook_t, cbm_json_like_value_shape_t, jl_array_t, jl_buffer_t, jl_edit_t, jl_file_snapshot_t, jl_fixture_t, jl_member_t (+122 more)

### Community 24 - "Regression repro tests"
Cohesion: 0.05
Nodes (131): RPExactReferenceSiteCase, RFile, RProj, rh_cleanup(), rh_index_files(), TEST, repro_issue408_workspace_crosspkg_import(), TEST (+123 more)

### Community 25 - "Graph buffer traversal & parallelism"
Cohesion: 0.05
Nodes (124): cbm_gbuf_edge_visitor_fn, kotlin_implicit_probe_t, parallel_result_mutator_fn, cbm_fopen(), cbm_gbuf_foreach_edge(), cbm_pipeline_find_lsp_resolution(), extract_grpc_service_method(), assert_c_family_preprocessed_collision_graph() (+116 more)

### Community 26 - "Activation transaction (install)"
Cohesion: 0.07
Nodes (121): activation_create_status_t, activation_file_identity_t, activation_native_file_t, activation_publish_status_t, activation_test_acl_status_t, activation_unlink_status_t, activation_windows_security_t, cbm_activation_transaction_before_absent_publish_for_test_fn (+113 more)

### Community 27 - "Pipeline lifecycle & store"
Cohesion: 0.08
Nodes (124): NamedEdgeObservation, ObjectScriptExportObservation, autoindex_thread(), cbm_pipeline_cancel(), cbm_pipeline_free(), cbm_pipeline_new(), cbm_pipeline_project_name(), cbm_pipeline_run() (+116 more)

### Community 28 - "Rust closure resolution"
Cohesion: 0.03
Nodes (124): TEST, find_resolved(), rustlsp_arc_clone(), rustlsp_cov_clo_find(), rustlsp_cov_clo_for_each(), rustlsp_cov_clo_inspect(), rustlsp_cov_clo_iter_filter(), rustlsp_cov_clo_iter_map() (+116 more)

### Community 29 - "YAML config editor"
Cohesion: 0.07
Nodes (115): cbm_yaml_lock_postcreate_test_hook_t, HANDLE, cbm_yaml_encode_double_quoted_scalar(), cbm_yaml_set_lock_postcreate_hook_for_testing(), yaml_add_item_range(), yaml_analyze_list(), yaml_analyze_mapping(), yaml_append_list_item_line() (+107 more)

### Community 30 - "Grammar build tests"
Cohesion: 0.06
Nodes (111): build_base_battery(), build_callable_battery(), build_pipeline_battery(), build_robustness(), build_struct_battery(), CBMLanguage, SUITE, TEST (+103 more)

### Community 31 - "Registry & type resolution"
Cohesion: 0.06
Nodes (107): cbm_fuzzy_result_t, qn_array_t, best_by_import_distance(), cbm_registry_t, cbm_resolution_t, candidate_count_penalty(), candidate_score(), cbm_confidence_band() (+99 more)

### Community 32 - "Project lock registry"
Cohesion: 0.07
Nodes (107): cbm_lock_registry_release_handle_t, cbm_lock_registry_stage_hook_fn, cbm_private_fork_condition_t, lock_registry_entry_t, lock_registry_fixture_t, lock_registry_waiter_t, cypher_deadline_arm(), cbm_lock_cancel_token_t (+99 more)

### Community 33 - "Search output & impact analysis"
Cohesion: 0.06
Nodes (109): cbm_edge_info_t, cbm_impact_summary_t, cbm_risk_level_t, bm25_file_pattern_like(), cbm_search_output_t, cbm_build_impact_summary(), cbm_ensure_case_insensitive(), cbm_extract_like_hints() (+101 more)

### Community 34 - "Daemon maintenance & version cohort"
Cohesion: 0.06
Nodes (107): cbm_daemon_maintenance_cancel_fn, cbm_version_cohort_daemon_presence_t, cbm_version_cohort_maintenance_presence_t, cbm_version_cohort_quiesce_fn, frontend_maintenance_fixture_t, cbm_daemon_maintenance_monitor_t, cbm_version_cohort_manager_t, cbm_daemon_maintenance_monitor_start() (+99 more)

### Community 35 - "Arena memory & shared registries"
Cohesion: 0.05
Nodes (106): cbm_arena_destroy(), cbm_arena_init(), clsp_tier2_shared_registry_readonly_c(), clsp_tier2_shared_registry_readonly_cpp(), registry_short_name_indexes(), seal_cs_shared_registry_readonly(), seal_go_shared_registry_readonly(), seal_py_shared_registry_readonly() (+98 more)

### Community 36 - "Diagnostics & logging"
Cohesion: 0.05
Nodes (99): cbm_log_sink_fn, CBMLogFormat, CBMLogLevel, CBMLogSinkMode, diagnostics_paths_t, append_trajectory(), FILE, HANDLE (+91 more)

### Community 37 - "FQN & relative import resolution"
Cohesion: 0.05
Nodes (105): cbm_pipeline_fqn_compute(), cbm_pipeline_fqn_folder(), cbm_pipeline_fqn_module(), cbm_pipeline_resolve_relative_import(), classify_relative_import(), fqn_bound_name_len(), join_segments(), path_append_segment() (+97 more)

### Community 38 - "Language definition extractors"
Cohesion: 0.04
Nodes (106): body_tokens_type_identifier(), c_caller_attribution(), TEST, clojure_function(), cmake_function(), cobol_paragraph(), commonlisp_defmacro(), commonlisp_defun() (+98 more)

### Community 39 - "Agent client probes & adapters"
Cohesion: 0.06
Nodes (98): adapter_sb_t, agent_json_scanner_t, agent_probe_t, cbm_agent_client_id_t, cbm_agent_client_profile_t, agent_client_marker_path(), agent_command_exists(), agent_continue_edit() (+90 more)

### Community 40 - "Subprocess management"
Cohesion: 0.06
Nodes (101): cbm_proc_opts_t, cbm_proc_poll_t, cbm_tail_result_t, LPPROC_THREAD_ATTRIBUTE_LIST, cbm_mkstemp(), cbm_proc_log_cb, cbm_proc_outcome_t, cbm_proc_result_t (+93 more)

### Community 41 - "Java LSP resolution tests"
Cohesion: 0.07
Nodes (102): CBMFileResult, TEST, count_resolved(), extract_java(), extract_java_at(), find_resolved(), jlsp_array_index(), jlsp_array_length_field() (+94 more)

### Community 42 - "LSP resolution probe tests"
Cohesion: 0.06
Nodes (102): LRP_File, LRP_Proj, cbm_store_t, SUITE, TEST, lrp_assert_calls(), lrp_c_s1_crossfile_call(), lrp_c_s2_funcptr_in_struct() (+94 more)

### Community 43 - "Watcher auto-sync"
Cohesion: 0.11
Nodes (96): cbm_index_fn, prune_fixture_t, cbm_store_open_memory(), cbm_store_t, cbm_watcher_free(), cbm_watcher_new(), cbm_watcher_poll_interval_ms(), cbm_watcher_poll_once() (+88 more)

### Community 44 - "Daemon conflicts & SHA-256"
Cohesion: 0.05
Nodes (97): cbm_daemon_conflict_log_test_hook_fn, cbm_sha256_ctx, posix_log_path_t, cbm_cli_sha256_file(), bounded_length(), BY_HANDLE_FILE_INFORMATION, cbm_daemon_build_identity_t, cbm_daemon_conflict_log_test_stage_t (+89 more)

### Community 45 - "Parallel extraction workers"
Cohesion: 0.05
Nodes (98): CBMCallArg, extract_worker_state_t, pp_err_list_t, resolve_ctx_t, resolve_worker_state_t, cbm_aligned_alloc(), cbm_max_file_bytes(), cbm_json_escape() (+90 more)

### Community 46 - "CLI main & hook admission"
Cohesion: 0.04
Nodes (82): cbm_hook_admission_t, main_build_identity_status_t, main_local_cli_mutation_t, main_local_maintenance_context_t, cbm_cli_exit_status_after_maintenance(), cbm_cli_mcp_result_is_error(), cbm_cli_set_version(), cbm_hook_admission_notice() (+74 more)

### Community 47 - "Multi-language extraction tests"
Cohesion: 0.04
Nodes (98): bash_function(), c_function(), c_struct(), cpp_class(), cpp_gtest_f_unique_name_issue1266(), cpp_gtest_same_name_collision_issue1266(), cpp_out_of_line_method_issue428(), csharp_class() (+90 more)

### Community 48 - "Path utils & profiling"
Cohesion: 0.05
Nodes (95): cbm_path_info_t, cbm_pipeline_generation_t, cbm_replacement_prepare_t, CBMStringRef, cbm_clock_gettime(), cbm_path_info_utf8(), cbm_remove_db_sidecars(), cbm_rename_noreplace() (+87 more)

### Community 49 - "Kotlin LSP resolution tests"
Cohesion: 0.07
Nodes (97): CBMFileResult, SUITE, TEST, count_exact_resolved_site(), count_exact_synthetic_call(), count_resolved(), count_synthetic_call(), extract_kotlin() (+89 more)

### Community 50 - "Private file locks (Windows)"
Cohesion: 0.07
Nodes (90): private_lock_fixture_t, private_win_identity_t, private_win_security_t, cbm_lock_registry_is_retired_for_test(), BOOL, BY_HANDLE_FILE_INFORMATION, cbm_private_file_lock_mode_t, cbm_private_file_lock_release_step_t (+82 more)

### Community 51 - "Python LSP resolution tests"
Cohesion: 0.07
Nodes (95): PyImportReferenceCounts, PyLSPContext, PyResolvedSiteCounts, bind_imports_into_ctx(), CBMArena, CBMFileResult, CBMResolvedCallArray, CBMTypeRegistry (+87 more)

### Community 52 - "Incremental update & ADR tools"
Cohesion: 0.06
Nodes (95): TEST, call_tool(), call_tool_timed(), count_by_label(), incr_full_has_functions(), tool_adr_default_mode(), tool_adr_get(), tool_adr_sections() (+87 more)

### Community 53 - "Node creation probes"
Cohesion: 0.06
Nodes (94): NcpLangFile, NcpLangProj, NcpMetrics, cbm_store_t, SUITE, TEST, ncp_cleanup(), ncp_count_label() (+86 more)

### Community 54 - "ADR management & Louvain"
Cohesion: 0.06
Nodes (93): cbm_adr_sections_t, cbm_adr_t, cbm_lg_t, cbm_pipeline_incremental_test_force_legacy_partial_once(), adr_append_line(), adr_render_section(), adr_save_section(), cbm_louvain_edge_t (+85 more)

### Community 55 - "Community 55"
Cohesion: 0.06
Nodes (89): GpdFile, GpdMetrics, GpdProj, cbm_store_t, SUITE, TEST, gpd_cleanup(), gpd_count_label() (+81 more)

### Community 56 - "Community 56"
Cohesion: 0.08
Nodes (85): cbm_text_precommit_test_hook_t, FILE, HANDLE, cbm_text_create_owned_document(), cbm_text_ensure_owned_document(), cbm_text_migrate_owned_document(), cbm_text_migrate_owned_document_mode(), cbm_text_owned_document_status() (+77 more)

### Community 57 - "Community 57"
Cohesion: 0.08
Nodes (87): cbm_build_vibe_mcp_body(), cbm_remove_vibe_mcp_owned(), cbm_upsert_vibe_mcp(), HANDLE, cbm_toml_escape_basic_string(), cbm_toml_remove_legacy_table(), cbm_toml_remove_owned_named_array_table(), cbm_toml_upsert_owned_named_array_table() (+79 more)

### Community 58 - "Community 58"
Cohesion: 0.06
Nodes (84): cbm_edge_t, cbm_store_count_edges(), cbm_store_find_edges_by_source(), cbm_store_find_edges_by_target(), cbm_store_find_edges_by_target_type(), cbm_store_find_edges_by_type(), cbm_store_find_node_by_id(), cbm_store_free_edges() (+76 more)

### Community 59 - "Community 59"
Cohesion: 0.10
Nodes (85): cbm_yaml_free(), cbm_yaml_get_bool(), cbm_yaml_get_float(), cbm_yaml_get_str(), cbm_yaml_has(), cbm_yaml_parse(), cli_yaml_has(), cli_yaml_parse_bool() (+77 more)

### Community 60 - "Community 60"
Cohesion: 0.08
Nodes (86): cbm_mcp_project_mutation_begin_fn, cbm_mcp_project_mutation_end_fn, cbm_mcp_project_mutation_try_begin_fn, cbm_mcp_quarantine_test_hook_fn, application_session_open(), cbm_daemon_client_id_t, cbm_rmdir(), cbm_file_exists() (+78 more)

### Community 61 - "Community 61"
Cohesion: 0.06
Nodes (80): cbm_lsh_entry_t, cbm_lsh_index_t, fp_entry_t, lsh_bucket_t, seen_set_t, sim_edge_buf_t, cbm_gbuf_t, cbm_minhash_t (+72 more)

### Community 62 - "Community 62"
Cohesion: 0.07
Nodes (80): CBMArena, cbm_path_base(), cbm_path_dir(), cbm_path_ext(), cbm_path_join(), cbm_path_join_n(), cbm_str_contains(), cbm_str_ends_with() (+72 more)

### Community 63 - "Community 63"
Cohesion: 0.07
Nodes (82): MN_LangFile, MN_LangProj, MN_Metrics, MN_TSNamespaceObservation, cbm_store_t, SUITE, TEST, matrix_new_constructs() (+74 more)

### Community 64 - "Community 64"
Cohesion: 0.05
Nodes (74): body_t, cbm_layout_level_t, cbm_layout_node_t, node_flags_t, node_id_entry_t, octree_node_t, cbm_ui_config_t, HANDLE (+66 more)

### Community 65 - "Community 65"
Cohesion: 0.07
Nodes (76): CaseIdentity, MatrixCase, ModuleArgumentCase, RoutineArgumentCase, ScopeMode, ast_node_match_count(), CBMFileResult, CBMLanguage (+68 more)

### Community 66 - "Community 66"
Cohesion: 0.03
Nodes (78): cov_bind_catch_param(), cov_bind_enhanced_for_array(), cov_bind_enhanced_for_iterable(), cov_bind_try_resources(), cov_bind_var_arraylist(), cov_conc_completable_supplyAsync(), cov_conc_reentrant_lock(), cov_ctrl_for_call() (+70 more)

### Community 67 - "Community 67"
Cohesion: 0.06
Nodes (73): caller_edge_ref_t, code_entry_t, config_entry_t, dep_entry_t, cbm_gbuf_find_by_label(), cbm_gbuf_node_t, cbm_gbuf_t, cbm_pipeline_ctx_t (+65 more)

### Community 68 - "Community 68"
Cohesion: 0.07
Nodes (76): GpfFile, GpfMetrics, GpfProj, cbm_store_t, SUITE, TEST, gpf_cleanup(), gpf_count_label() (+68 more)

### Community 69 - "Community 69"
Cohesion: 0.03
Nodes (77): require_resolved(), tslsp_alias_chain(), tslsp_async_iter_for_await_of(), tslsp_async_iterator_next_promise(), tslsp_await_promise_unwrap(), tslsp_class_chained_field_method(), tslsp_class_factory_with_extends(), tslsp_class_implements_interface() (+69 more)

### Community 70 - "Community 70"
Cohesion: 0.10
Nodes (72): cbm_daemon_callback_batch_t, cbm_daemon_client_t, cbm_daemon_coordinator_hooks_t, cbm_daemon_coordinator_state_t, cbm_daemon_job_state_t, cbm_daemon_job_t, cbm_daemon_subscription_t, cbm_daemon_watch_t (+64 more)

### Community 71 - "Community 71"
Cohesion: 0.04
Nodes (61): parity_case_t, cbm_store_t, SUITE, TEST, count_distinct_qns(), count_nodes_by_name(), invariant_discovery_always_skip_dirs(), invariant_discovery_fast_skip_dirs() (+53 more)

### Community 72 - "Community 72"
Cohesion: 0.06
Nodes (73): alias_config_hit_t, cbm_dir_t, cli_binary_validator_t, extract_install_args_t, cbm_activation_transaction_deferred_path(), cbm_activation_transaction_status_message(), cbm_activation_transaction_target_path(), build_update_url() (+65 more)

### Community 73 - "Community 73"
Cohesion: 0.07
Nodes (74): EILangFile, EILangFixtureFile, EILangProj, cbm_store_t, SUITE, TEST, edge_imports(), ei_cleanup() (+66 more)

### Community 74 - "Community 74"
Cohesion: 0.12
Nodes (71): cbm_yaml_precommit_test_hook_t, cbm_yaml_remove_mapping_entry(), cbm_yaml_remove_mapping_sequence_item(), cbm_yaml_remove_owned_mapping_entry(), cbm_yaml_remove_string_list_item(), cbm_yaml_set_precommit_hook_for_testing(), cbm_yaml_set_prepublish_hook_for_testing(), cbm_yaml_upsert_mapping_entry() (+63 more)

### Community 75 - "Community 75"
Cohesion: 0.09
Nodes (71): EtFile, EtProj, cbm_store_count_edges_by_type(), async_calls_bullmq_js(), async_calls_celery_python(), async_calls_kafkajs_ts(), async_calls_sidekiq_ruby(), async_calls_sqs_go() (+63 more)

### Community 76 - "Community 76"
Cohesion: 0.08
Nodes (67): cbm_pipeline_lsp_reference_index_entry_t, cbm_pipeline_lsp_reference_index_t, cbm_lsp_bare_segment(), cbm_pipeline_call_callee_leaf(), cbm_pipeline_call_reference_usage_fallback_allowed(), cbm_pipeline_find_lsp_reference(), cbm_pipeline_find_lsp_reference_in_graph(), cbm_pipeline_find_lsp_reference_indexed_in_graph() (+59 more)

### Community 77 - "Community 77"
Cohesion: 0.08
Nodes (68): CBMCallArray, CBMImplTrait, CBMModuleDefIndex, CBMRustLSPDef, pxc_module_entry_t, cbm_file_info_t, cbm_gbuf_node_t, cbm_gbuf_t (+60 more)

### Community 78 - "Community 78"
Cohesion: 0.08
Nodes (70): GpeFile, GpeMetrics, GpeProj, cbm_store_t, SUITE, TEST, gpe_cleanup(), gpe_count_label() (+62 more)

### Community 79 - "Community 79"
Cohesion: 0.06
Nodes (64): cbm_pipeline_fqn_module_dir(), build_import_map(), build_return_type_table(), cbm_file_info_t, cbm_gbuf_node_t, cbm_gbuf_t, cbm_pipeline_ctx_t, cbm_regex_t (+56 more)

### Community 80 - "Community 80"
Cohesion: 0.10
Nodes (69): CBMFileResult, SUITE, TEST, count_resolved_with_strategy(), cs_lsp(), cslsp_array_element_access(), cslsp_as_expression(), cslsp_async_await() (+61 more)

### Community 81 - "Community 81"
Cohesion: 0.06
Nodes (66): cbm_daemon_host_cleanup_release_for_test_fn, cbm_daemon_host_config_t, cbm_daemon_host_http_free_refusal_test_result_t, cbm_daemon_host_http_reconcile_test_result_t, host_state_t, atomic_int, cbm_daemon_ipc_endpoint_t, cbm_daemon_ipc_lifetime_reservation_t (+58 more)

### Community 82 - "Community 82"
Cohesion: 0.08
Nodes (65): arena_grow(), CBMArena, cbm_arena_alloc(), cbm_arena_calloc(), cbm_arena_init_sized(), cbm_arena_reset(), cbm_arena_sprintf(), cbm_arena_strdup() (+57 more)

### Community 83 - "Community 83"
Cohesion: 0.09
Nodes (65): GrammarCase, LangFile, LangMetrics, LangProj, breadth_diag(), cbm_store_t, CBMLanguage, SUITE (+57 more)

### Community 84 - "Community 84"
Cohesion: 0.16
Nodes (63): CP_File, CP_Proj, cbm_store_t, SUITE, TEST, convergence_probe(), cp_anon_class_java(), cp_anon_object_kotlin() (+55 more)

### Community 85 - "Community 85"
Cohesion: 0.11
Nodes (62): CBMFileResult, CBMResolvedCallArray, SUITE, TEST, count_resolved(), extract_go(), find_resolved(), find_resolved_arr() (+54 more)

### Community 86 - "Community 86"
Cohesion: 0.11
Nodes (57): cbm_cross_repo_after_insert_test_hook_t, cr_match_result_t, cr_run_context_t, cr_run_status_t, cross_repo_fixture_t, cbm_validate_project_name(), add_match_count(), build_cross_props() (+49 more)

### Community 87 - "Community 87"
Cohesion: 0.09
Nodes (60): cbm_dockerfile_result_t, cbm_dotenv_result_t, cbm_helm_chart_t, cbm_shell_result_t, cbm_terraform_result_t, cbm_tf_variable_t, cbm_is_cloudbuild_file(), cbm_is_compose_file() (+52 more)

### Community 88 - "Community 88"
Cohesion: 0.09
Nodes (60): GpaFile, GpaMetrics, GpaProj, cbm_store_t, SUITE, TEST, gpa_cleanup(), gpa_count_label() (+52 more)

### Community 89 - "Community 89"
Cohesion: 0.03
Nodes (61): phplsp_abstract_class_method(), phplsp_abstract_via_concrete(), phplsp_anonymous_function_arg(), phplsp_arrow_function_typed_param(), phplsp_assert_then_chain(), phplsp_catch_binding(), phplsp_chain_through_this_field(), phplsp_chained_with_intermediate_var() (+53 more)

### Community 90 - "Community 90"
Cohesion: 0.08
Nodes (59): ArgUsageCase, CompoundAssignmentCase, SignaturePositionCase, cbm_store_t, CBMFileResult, CBMUsageKind, RFile, SUITE (+51 more)

### Community 91 - "Community 91"
Cohesion: 0.11
Nodes (59): binding_t, cbm_query_t, cbm_return_clause_t, cbm_where_clause_t, ret_agg_entry_t, apply_string_func(), binding_get(), binding_get_edge() (+51 more)

### Community 92 - "Community 92"
Cohesion: 0.08
Nodes (58): cbm_discover_opts_t, cbm_discover_status_t, file_list_t, ascii_ieq(), cbm_dirent_t, cbm_file_info_t, cbm_gitignore_t, cbm_ignored_file_t (+50 more)

### Community 93 - "Community 93"
Cohesion: 0.09
Nodes (59): cbm_node_free_fields(), cbm_store_check_integrity(), cbm_store_count_nodes(), cbm_store_find_node_by_qn(), cbm_store_find_node_ids_by_qns(), cbm_store_upsert_node_batch(), cbm_pipeline_t, observe_publish_boundary() (+51 more)

### Community 94 - "Community 94"
Cohesion: 0.07
Nodes (45): cbm_parallel_fn, cbm_parallel_for_opts_t, cbm_system_info_t, cbm_default_worker_count(), cbm_system_info(), detect_system_bsd(), detect_system_macos(), detect_system_windows() (+37 more)

### Community 95 - "Community 95"
Cohesion: 0.11
Nodes (57): GP_File, GP_Proj, cbm_store_t, CBMLanguage, TEST, gp_cleanup(), gp_count_label(), gp_extract_has_base_class() (+49 more)

### Community 96 - "Community 96"
Cohesion: 0.09
Nodes (58): GpgFile, GpgMetrics, GpgProj, cbm_store_t, SUITE, TEST, gpg_cleanup(), gpg_count_label() (+50 more)

### Community 97 - "Community 97"
Cohesion: 0.08
Nodes (58): cbm_build_cmdline(), cbm_exec_no_shell(), cbm_pclose(), cbm_popen_last_was_isolated(), cbm_validate_shell_arg(), SUITE, TEST, cmdline_embedded_quote_is_escaped() (+50 more)

### Community 98 - "Community 98"
Cohesion: 0.07
Nodes (51): cbm_cross_repo_result_t, IBMetrics, cbm_cross_repo_match(), cbm_store_t, CBMLanguage, rh_count_edges(), rh_count_label(), rh_extract_crashes() (+43 more)

### Community 99 - "Community 99"
Cohesion: 0.10
Nodes (56): cbm_embedded_file_t, cbm_http_project_mutation_begin_fn, cbm_http_project_mutation_end_fn, cbm_is_dir(), main_resolve_executable(), cbm_embedded_lookup(), append_roots_json(), cbm_http_conn_t (+48 more)

### Community 100 - "Community 100"
Cohesion: 0.12
Nodes (57): ProbeLangFile, ProbeLangProj, cbm_store_t, SUITE, TEST, glsl_function_nodes(), glsl_struct_node(), glsl_vertex_shader_functions() (+49 more)

### Community 101 - "Community 101"
Cohesion: 0.11
Nodes (54): artifact_file_error_t, artifact_snapshot_tmp_t, artifact_export_fail(), artifact_path(), artifact_snapshot_tmp_close(), artifact_snapshot_tmp_open(), cbm_artifact_commit(), cbm_artifact_exists() (+46 more)

### Community 102 - "Community 102"
Cohesion: 0.10
Nodes (57): cbm_pipeline_test_hook_fn, cbm_scan_project_env_urls(), cbm_pipeline_incremental_test_before_final_manifest_once(), cbm_pipeline_incremental_test_fail_after_stage_dump_once(), cbm_pipeline_incremental_test_last_route(), cbm_pipeline_incremental_test_reset_faults(), cbm_store_clear_file_hash(), cbm_store_get_file_hash() (+49 more)

### Community 103 - "Community 103"
Cohesion: 0.08
Nodes (52): batch_resolve_ctx_t, cbm_sem_src_entry_t, cooccur_int8_ctx_t, cooccur_sparse_ctx_t, finalize_params_t, reverse_index_t, cbm_sem_corpus_t, phase3c_export_token_vectors() (+44 more)

### Community 104 - "Community 104"
Cohesion: 0.10
Nodes (54): ha_lifecycle_dialect_t, cbm_mcp_server_t, yyjson_val, cbm_cmd_hook_augment(), cbm_hook_augment_arm_deadline(), cbm_hook_augment_format_context_for_testing(), cbm_hook_augment_invocation_supported(), cbm_hook_augment_invocation_supported_for_testing() (+46 more)

### Community 105 - "Community 105"
Cohesion: 0.10
Nodes (55): MKC_File, MKC_Proj, cbm_store_t, SUITE, TEST, matrix_known_classes(), mkc_c1_cpp_constructor_samefile(), mkc_c1_ruby_type_new() (+47 more)

### Community 106 - "Community 106"
Cohesion: 0.10
Nodes (55): OrderedSignatureLanguage, add_csharp_seeded_method(), add_fixture_type(), add_php_seeded_method(), alloc_test_registry(), build_java_cross_registry_for_contract(), build_kotlin_cross_registry_for_contract(), build_php_cross_registry_for_contract() (+47 more)

### Community 107 - "Community 107"
Cohesion: 0.09
Nodes (49): cbm_canonicalize_drive(), cbm_mmap_read(), cbm_munmap(), cbm_now_ns(), cbm_nprocs(), cbm_platform_scale_counter_ns(), cbm_platform_scale_fraction(), platform_copy_environment_value() (+41 more)

### Community 108 - "Community 108"
Cohesion: 0.08
Nodes (54): build_api_vec(), build_deco_vec(), build_type_vec(), cbm_sem_vec_t, collect_worker(), json_str_array(), tokenize_json_array_field(), blend_worker() (+46 more)

### Community 109 - "Community 109"
Cohesion: 0.15
Nodes (53): BehaviorCase, ast_kind_count(), begin_routine_case(), CBMFileResult, CBMMacroTable, SUITE, TEST, TSNode (+45 more)

### Community 110 - "Community 110"
Cohesion: 0.11
Nodes (51): CBMImport, cbm_strndup(), at_prefix(), build_entry_path(), cbm_gbuf_node_t, cbm_pipeline_ctx_t, cbm_pkg_entries_t, yyjson_val (+43 more)

### Community 111 - "Community 111"
Cohesion: 0.10
Nodes (49): cbm_ws_manifest_t, cbm_ws_verdict_t, cbm_workspace_cache_dir(), cbm_workspace_classify_root(), cbm_workspace_grant_add(), cbm_workspace_grant_list(), cbm_workspace_grant_path(), cbm_workspace_home_dir() (+41 more)

### Community 112 - "Community 112"
Cohesion: 0.09
Nodes (47): deferred_edge_buf_t, hyperplane_row_t, score_ctx_t, sem_bucket_t, cbm_gbuf_node_t, cbm_gbuf_t, cbm_pipeline_ctx_t, cbm_sem_config_t (+39 more)

### Community 113 - "Community 113"
Cohesion: 0.11
Nodes (51): cbm_mem_budget(), cbm_mem_collect(), cbm_mem_init(), cbm_mem_peak_rss(), cbm_mem_ram_fraction_for_total(), cbm_mem_resolve_budget(), cbm_mem_rss(), cbm_mem_worker_budget() (+43 more)

### Community 114 - "Community 114"
Cohesion: 0.15
Nodes (50): cbm_toml_precommit_test_hook_t, cbm_toml_remove_managed_block(), cbm_toml_remove_named_array_table(), cbm_toml_set_precommit_hook_for_testing(), cbm_toml_set_prepublish_hook_for_testing(), cbm_toml_upsert_managed_block(), cbm_toml_upsert_named_array_table(), SUITE (+42 more)

### Community 115 - "Community 115"
Cohesion: 0.14
Nodes (50): CBMFileResult, SUITE, TEST, extract_py(), find_resolved(), py_lsp_stress(), require_resolved(), stress_abc_abstractmethod() (+42 more)

### Community 116 - "Community 116"
Cohesion: 0.10
Nodes (39): RuntimeError, assert_coordination_idle(), assert_indexed_tool_response(), assert_no_activation_artifacts(), assert_rpc_cancelled(), assert_rpc_success(), check(), create_local_update_release() (+31 more)

### Community 117 - "Community 117"
Cohesion: 0.08
Nodes (47): search_scratch_t, FILE, cbm_getline(), cbm_path_for_file_api(), cbm_strcasestr(), cbm_unlink(), win_mkdtemp_private_create(), cbm_path_to_wide() (+39 more)

### Community 118 - "Community 118"
Cohesion: 0.13
Nodes (45): cbm_gitignore_t, cbm_gitignore_free(), cbm_gitignore_load(), cbm_gitignore_match_result(), cbm_gitignore_matches(), cbm_gitignore_merge(), cbm_gitignore_parse(), gi_add_pattern() (+37 more)

### Community 119 - "Community 119"
Cohesion: 0.22
Nodes (48): cbm_condition_t, cbm_parse_result_t, cbm_return_item_t, cbm_token_t, parser_t, advance(), cbm_parse(), cbm_parse_free() (+40 more)

### Community 120 - "Community 120"
Cohesion: 0.16
Nodes (46): profile_buffer_t, profile_tool_t, access_valid(), append_codex_profile(), append_csv_mcp_tools(), append_permission_mcp_tools(), append_toml_mcp_tools(), append_yaml_identity() (+38 more)

### Community 121 - "Community 121"
Cohesion: 0.07
Nodes (48): cbm_cypher_parse(), cbm_query_free(), cypher_error_call(), cypher_error_create(), cypher_error_delete(), cypher_error_merge(), cypher_error_set(), cypher_issue874_where_unsupported_func_error() (+40 more)

### Community 122 - "Community 122"
Cohesion: 0.12
Nodes (45): ES_LangFile, ES_LangProj, cbm_store_t, SUITE, TEST, edge_structural(), es_calls_crossfile_c(), es_calls_crossfile_cpp() (+37 more)

### Community 123 - "Community 123"
Cohesion: 0.11
Nodes (41): cbm_http_span_info_t, cbm_trace_resource_t, cbm_trace_span_t, cbm_calculate_p99(), cbm_extract_http_info(), cbm_extract_path_from_url(), cbm_extract_service_name(), cbm_parse_duration() (+33 more)

### Community 124 - "Community 124"
Cohesion: 0.12
Nodes (42): decode_struct_profile(), accumulate_control_flow(), accumulate_data_flow(), accumulate_expressions(), accumulate_halstead(), cbm_ast_profile_t, TSNode, cbm_ast_profile_compute() (+34 more)

### Community 125 - "Community 125"
Cohesion: 0.19
Nodes (42): LBBindingSite, CBMFileResult, CBMLanguage, SUITE, TEST, lb_binding_site(), lb_extract(), lb_identifier_offset() (+34 more)

### Community 126 - "Community 126"
Cohesion: 0.12
Nodes (42): application_worker_cancel_default(), application_worker_destroy_default(), application_worker_log_path_default(), application_worker_poll_default(), application_worker_start_default(), cbm_daemon_application_worker_t, cbm_index_worker_poll_t, cbm_file_size() (+34 more)

### Community 127 - "Community 127"
Cohesion: 0.09
Nodes (24): McpError, McpServer, Exception, Minimal MCP stdio client for the Windows red-test suite. Drives a real…, graph_function_count(), main(), Regression guard for issue #996 — dump phase must write the graph DB into a…, index_and_count() (+16 more)

### Community 128 - "Community 128"
Cohesion: 0.15
Nodes (41): cbm_slab_destroy_thread(), cbm_slab_install(), cbm_slab_test_calloc(), cbm_slab_test_free(), cbm_slab_test_malloc(), cbm_slab_test_realloc(), slab_calloc_zeroed(), slab_cross_thread_free_is_safe() (+33 more)

### Community 129 - "Community 129"
Cohesion: 0.14
Nodes (38): cbm_vmem_alloc(), cbm_vmem_allocated(), cbm_vmem_budget(), cbm_vmem_free(), cbm_vmem_init(), cbm_vmem_over_budget(), cbm_vmem_peak(), cbm_vmem_worker_budget() (+30 more)

### Community 130 - "Community 130"
Cohesion: 0.13
Nodes (38): cbm_watcher_project_mutation_begin_fn, cbm_watcher_project_mutation_end_fn, cbm_watcher_project_pruned_fn, project_state_t, root_status_t, cbm_watcher_t, wchar_t, cbm_watcher_root_missing_errno() (+30 more)

### Community 131 - "Community 131"
Cohesion: 0.05
Nodes (40): all_results_have_label(), count_in_response(), tool_qg_count_functions(), tool_qg_empty_result(), tool_qg_match_contains(), tool_qg_match_defines(), tool_qg_match_edges(), tool_qg_match_imports() (+32 more)

### Community 132 - "Community 132"
Cohesion: 0.12
Nodes (37): cbm_sock_t, host_http_thread(), cbm_http_server_run(), cbm_http_conn_t, cbm_http_req_t, cbm_http_conn_response_bytes(), cbm_http_conn_status(), cbm_http_path_match() (+29 more)

### Community 133 - "Community 133"
Cohesion: 0.14
Nodes (37): assert_lsp_strategy(), assert_rust_dispatch_files(), RFile, SUITE, TEST, repro_lsp_kt_any(), repro_lsp_kt_callable_ref(), repro_lsp_kt_constructor() (+29 more)

### Community 134 - "Community 134"
Cohesion: 0.09
Nodes (37): cbm_cli_activation_mutation_fn, cli_activation_production_context_t, cbm_activation_transaction_refusal_note(), cbm_cli_activation_lock_t, cbm_cli_activation_ops_t, cbm_daemon_runtime_activation_action_t, cbm_daemon_runtime_activation_result_t, cbm_version_cohort_lease_t (+29 more)

### Community 135 - "Community 135"
Cohesion: 0.14
Nodes (37): cbm_store_t, SUITE, delete_file_at(), get_edge_count(), get_edge_count_by_type(), get_node_count(), has_function(), incr_accuracy_vs_full() (+29 more)

### Community 136 - "Community 136"
Cohesion: 0.11
Nodes (34): file_type_t, eval_comparison_op(), cbm_regex_t, cbm_regmatch_t, cbm_regcomp(), cbm_regexec(), cbm_regfree(), translate_flags() (+26 more)

### Community 137 - "Community 137"
Cohesion: 0.15
Nodes (35): assert_lsp_strategy(), assert_method_reference_semantics(), assert_no_resolvable_edge(), SUITE, TEST, repro_lsp_cs_ctor(), repro_lsp_cs_ctor_synthetic(), repro_lsp_cs_extension_method() (+27 more)

### Community 138 - "Community 138"
Cohesion: 0.20
Nodes (35): cbm_http_index_executor_fn, cbm_http_server_port(), cbm_http_server_set_index_executor(), atomic_int, th_http(), th_http_raw(), th_server_start(), th_server_stop() (+27 more)

### Community 139 - "Community 139"
Cohesion: 0.10
Nodes (33): cbm_index_worker_argv_status_t, cbm_index_worker_invocation_t, atomic_int, cbm_index_worker_result_t, cbm_proc_log_cb, cbm_index_set_worker_role(), cbm_index_set_worker_role_options(), cbm_index_spawn_worker() (+25 more)

### Community 140 - "Community 140"
Cohesion: 0.22
Nodes (34): CBMFileResult, CBMLanguage, SUITE, TEST, call_count(), call_reference_count(), call_short_name(), definition_count() (+26 more)

### Community 141 - "Community 141"
Cohesion: 0.23
Nodes (31): CBMInternPool, cbm_intern(), cbm_intern_bytes(), cbm_intern_count(), cbm_intern_create(), cbm_intern_free(), cbm_intern_n(), intern_hash() (+23 more)

### Community 142 - "Community 142"
Cohesion: 0.11
Nodes (32): frontend_cancellation_route_t, frontend_item_t, frontend_state_t, cbm_daemon_runtime_application_token_t, cbm_daemon_runtime_client_t, FILE, cbm_daemon_frontend_mcp_run(), frontend_end_request() (+24 more)

### Community 143 - "Community 143"
Cohesion: 0.15
Nodes (33): import_case_t, CBMFileResult, CBMLanguage, SUITE, TEST, csharp_import_table(), csharp_local_name_last_segment(), do_extract() (+25 more)

### Community 144 - "Community 144"
Cohesion: 0.17
Nodes (28): cbm_path_alias_collection_t, cbm_path_alias_map_t, cbm_load_path_aliases(), cbm_load_path_aliases_excluded(), cbm_path_alias_collection_free(), cbm_path_alias_find_for_file(), cbm_path_alias_resolve(), free_alias_map() (+20 more)

### Community 145 - "Community 145"
Cohesion: 0.18
Nodes (33): cbm_node_pattern_t, cbm_pattern_t, cbm_prop_filter_t, cbm_rel_pattern_t, binding_copy(), binding_free(), binding_set(), binding_set_edge() (+25 more)

### Community 146 - "Community 146"
Cohesion: 0.12
Nodes (25): cbm_http_parse_head(), SUITE, TEST, daemon_host_http_thread_create_failure_cancels_scheduled_run(), git_context_resolve_no_hang_under_live_ui_sockets(), httpd(), httpd_parse_incomplete_head_needs_more(), httpd_parse_origin_case_insensitive() (+17 more)

### Community 147 - "Community 147"
Cohesion: 0.17
Nodes (31): rh_index(), cbm_node_t, cbm_store_t, SUITE, TEST, find_call_edge_to_helper(), repro_invariant_lsp_rescue(), repro_invariant_lsp_rescue_props() (+23 more)

### Community 148 - "Community 148"
Cohesion: 0.16
Nodes (32): assert_both_return_chains(), assert_contextual_callback_uses_selected_overload(), assert_exact_symbol_import_overload_returns(), assert_free_function_overload_returns(), assert_namespace_overload_returns(), assert_no_shadowed_return_chains(), assert_parameter_shadows_free_function(), assert_parameter_shadows_namespace() (+24 more)

### Community 149 - "Community 149"
Cohesion: 0.07
Nodes (33): CBMLanguage, CBMMacroTable, extract_cfscript_issue38(), extract_gdscript_issue186(), extract_helm_templates_issue338(), extract_perl_builtin_call_is_function_not_method(), extract_qml_issue42(), extract_r_dollar_call_issue219() (+25 more)

### Community 150 - "Community 150"
Cohesion: 0.09
Nodes (25): cbm_mem_budget_t, cbm_mem_map_t, cbm_mem_ownership_audit_t, cbm_mem_win_census_t, mi_heap_area_t, mi_heap_t, mi_option_t, cbm_mem_audit_ownership() (+17 more)

### Community 151 - "Community 151"
Cohesion: 0.15
Nodes (31): cbm_store_open_path_existing(), SUITE, TEST, call_tool(), create_test_project(), index_reports_excluded_subtrees_issue411(), integ_index_has_calls(), integ_index_has_edges() (+23 more)

### Community 152 - "Community 152"
Cohesion: 0.15
Nodes (30): CBMFileResult, CBMLanguage, SUITE, TEST, cpp_large_templated_header_no_crash_issue424(), express_routes_exceed_512(), extract(), go_calls_exceed_1024() (+22 more)

### Community 153 - "Community 153"
Cohesion: 0.10
Nodes (28): cbm_daemon_frontend_is_cancellation_notification(), cbm_daemon_client_id_t, cbm_daemon_runtime_application_session_t, cbm_daemon_runtime_application_status_t, cbm_daemon_runtime_application_token_t, cbm_version_cohort_quiesce_result_t, SUITE, TEST (+20 more)

### Community 154 - "Community 154"
Cohesion: 0.15
Nodes (27): cbm_dump_verify_is_degraded(), cbm_dump_verify_min_ratio(), SUITE, TEST, dump_verify(), dump_verify_count_error(), dump_verify_edges_shrank_nodes_ok(), dump_verify_growth() (+19 more)

### Community 155 - "Community 155"
Cohesion: 0.12
Nodes (29): SUITE, TEST, da_clear(), da_clear_then_push(), da_free(), da_free_then_push(), da_growth(), da_insert() (+21 more)

### Community 156 - "Community 156"
Cohesion: 0.14
Nodes (29): append_json_str_array(), append_json_string(), build_def_props(), cbm_file_info_t, cbm_gbuf_node_t, cbm_pipeline_ctx_t, cbm_read_status_t, CBMArena (+21 more)

### Community 157 - "Community 157"
Cohesion: 0.17
Nodes (29): assert_lsp_strategy(), assert_lsp_strategy_files(), assert_no_resolvable_edge(), assert_no_resolvable_edge_files(), RFile, SUITE, TEST, repro_lsp_go_direct() (+21 more)

### Community 158 - "Community 158"
Cohesion: 0.17
Nodes (28): go_imethod_t, cbm_gbuf_find_by_id(), build_import_map(), cbm_file_info_t, cbm_gbuf_node_t, cbm_pipeline_ctx_t, cbm_registry_t, CBMDefinition (+20 more)

### Community 159 - "Community 159"
Cohesion: 0.17
Nodes (28): k8s_record_array_t, k8s_record_t, cbm_infra_qn(), cbm_file_info_t, cbm_gbuf_node_t, cbm_pipeline_ctx_t, CBMFileResult, cbm_pipeline_pass_k8s() (+20 more)

### Community 160 - "Community 160"
Cohesion: 0.08
Nodes (29): CBMFileResult, CBMLanguage, count_calls(), extract_dts(), extract_js(), extract_with(), find_resolved(), ts_same_leaf_render_occurrences_are_exact() (+21 more)

### Community 161 - "Community 161"
Cohesion: 0.15
Nodes (28): cbm_pkg_entries_t, merge_pkg_entries(), cbm_file_info_t, cbm_pkg_entries_free(), cbm_pkg_entries_init(), cbm_pkgmap_build(), cbm_pkgmap_build_from_files(), cbm_pkgmap_build_from_repo() (+20 more)

### Community 162 - "Community 162"
Cohesion: 0.26
Nodes (27): CBMLanguage, SUITE, TEST, repro_grammar_shells(), repro_grammar_shells_awk(), repro_grammar_shells_bash(), repro_grammar_shells_devicetree(), repro_grammar_shells_fennel() (+19 more)

### Community 163 - "Community 163"
Cohesion: 0.08
Nodes (28): assert_cpp_family_preprocessed_collision_isolated(), assert_cpp_family_repeated_method_occurrences(), CBMFileResult, CBMLanguage, clsp_c_global_initializer_does_not_inherit_previous_function_caller(), clsp_c_nested_function_pointer_shadow_restores_outer_target(), clsp_c_preprocessed_coordinate_collision_isolated(), clsp_c_reassigned_function_pointer_calls_join_exact_occurrences() (+20 more)

### Community 164 - "Community 164"
Cohesion: 0.21
Nodes (27): assert_perl_repeated_exact_join(), CBMFileResult, CBMResolvedCall, SUITE, TEST, extract_perl(), find_resolved(), find_resolved_with_strategy() (+19 more)

### Community 165 - "Community 165"
Cohesion: 0.20
Nodes (24): cbm_userext_t, cbm_userconfig_t, CBMLanguage, yyjson_val, cbm_get_user_lang_config(), cbm_set_user_lang_config(), cbm_userconfig_free(), cbm_userconfig_load() (+16 more)

### Community 166 - "Community 166"
Cohesion: 0.26
Nodes (26): cli_activation_fake_t, cbm_cli_activation_test_ops_installed(), cbm_cli_set_activation_ops_for_test(), cbm_cli_set_activation_runtime_parent_for_test(), cbm_set_auto_answer_for_test(), cbm_cli_activation_ops_t, cli_activation_commands_reject_malformed_and_unknown_flags(), cli_activation_fake_ops() (+18 more)

### Community 167 - "Community 167"
Cohesion: 0.15
Nodes (25): inherit_case_t, rust_impl_case_t, bases_contain(), bases_contain_substr(), bases_count(), CBMDefinition, CBMFileResult, SUITE (+17 more)

### Community 168 - "Community 168"
Cohesion: 0.16
Nodes (24): cbm_daemon_ipc_endpoint_t, cbm_lock_cancel_token_t, cbm_private_file_lock_status_t, cbm_project_lock_lease_t, cbm_project_lock_manager_t, cbm_project_lock_acquire(), cbm_project_lock_lease_release(), cbm_project_lock_manager_free() (+16 more)

### Community 169 - "Community 169"
Cohesion: 0.14
Nodes (25): cbm_case_expr_t, cbm_func_arg_t, result_builder_t, build_default_columns(), build_return_columns(), build_star_columns(), cond_func_fields_free(), execute_return_clause() (+17 more)

### Community 170 - "Community 170"
Cohesion: 0.17
Nodes (24): cbm_validate_shell_path_arg(), append_fmt_checked(), cbm_git_context_t, cbm_git_context_branch_qn(), cbm_git_context_free(), cbm_git_context_props_json(), cbm_git_context_resolve(), derive_canonical_root() (+16 more)

### Community 171 - "Community 171"
Cohesion: 0.24
Nodes (25): cbm_http_server_set_watcher(), cbm_watcher_t, th_server_start_with_mutation_guard(), th_server_start_with_watcher(), th_ui_mutation_guard_init(), ui_adr_equals(), ui_adr_seed(), ui_delete_db_path() (+17 more)

### Community 172 - "Community 172"
Cohesion: 0.29
Nodes (24): CBMLanguage, SUITE, TEST, misc_pipeline_battery(), misc_robustness(), misc_single_file_battery(), repro_grammar_misc(), repro_grammar_misc_assembly() (+16 more)

### Community 173 - "Community 173"
Cohesion: 0.19
Nodes (24): assert_deep_pointer_return_arity(), assert_local_chained_target(), assert_reference_return_operator_arity(), assert_ts_interface_overload_return_chains(), CBMLanguage, CBMResolvedCallArray, SUITE, TEST (+16 more)

### Community 174 - "Community 174"
Cohesion: 0.21
Nodes (23): assert_lsp_strategy(), assert_no_resolvable_edge(), SUITE, TEST, repro_lsp_c_cpp(), repro_lsp_cpp_adl(), repro_lsp_cpp_base_dispatch(), repro_lsp_cpp_constructor() (+15 more)

### Community 175 - "Community 175"
Cohesion: 0.15
Nodes (23): ac(), ac_batch_scan(), ac_batch_scan_detailed(), ac_build_multiple(), ac_build_single(), ac_compact_alphabet_extended(), ac_custom_alphabet(), ac_free_double_call() (+15 more)

### Community 176 - "Community 176"
Cohesion: 0.15
Nodes (20): posix_spawn_file_actions_t, posix_spawnattr_t, bootstrap_arg_is(), bootstrap_child_close_fds(), bootstrap_daemon_grandchild(), bootstrap_darwin_reaper_start(), bootstrap_darwin_spawn_state_init(), bootstrap_find_arg() (+12 more)

### Community 177 - "Community 177"
Cohesion: 0.19
Nodes (21): cbm_daemon_process_role_requires_client(), bootstrap_fake_spawn(), cbm_daemon_bootstrap_launch_spec_t, cbm_daemon_process_role_t, SUITE, TEST, classify(), daemon_bootstrap() (+13 more)

### Community 178 - "Community 178"
Cohesion: 0.32
Nodes (22): CBMLanguage, SUITE, TEST, pipeline_battery(), repro_grammar_scientific(), repro_grammar_scientific_agda(), repro_grammar_scientific_apex(), repro_grammar_scientific_cairo() (+14 more)

### Community 179 - "Community 179"
Cohesion: 0.22
Nodes (22): cbm_config_t, cbm_cmd_config(), cbm_config_close(), cbm_config_delete(), cbm_config_get(), cbm_config_get_bool(), cbm_config_get_int(), cbm_config_open() (+14 more)

### Community 180 - "Community 180"
Cohesion: 0.14
Nodes (21): detect_file_language(), CBMLanguage, cbm_disambiguate_cls(), cbm_disambiguate_inc(), cbm_disambiguate_m(), cbm_language_name(), has_magma_callable_pattern(), has_magma_end_markers() (+13 more)

### Community 181 - "Community 181"
Cohesion: 0.12
Nodes (21): cbm_json_mcp_command_availability_t, HKEY, BY_HANDLE_FILE_INFORMATION, HANDLE, wchar_t, cbm_json_mcp_command_availability(), cbm_json_mcp_command_path_probe_safe(), cbm_json_mcp_command_path_probe_safe_for_platform() (+13 more)

### Community 182 - "Community 182"
Cohesion: 0.15
Nodes (19): CBMDefinition, CBMFileResult, CBMLanguage, SUITE, TEST, decorators_contain(), find_def(), repro_issue382() (+11 more)

### Community 183 - "Community 183"
Cohesion: 0.16
Nodes (20): cbm_daemon_runtime_status_t, cbm_daemon_runtime_stop_result_t, cbm_daemon_frame_t, cbm_daemon_frame_type_t, cbm_daemon_frame_header_decode(), cbm_daemon_frame_header_encode(), frame_type_valid(), cbm_daemon_frame_t (+12 more)

### Community 184 - "Community 184"
Cohesion: 0.18
Nodes (17): cbm_mem_profile_totals_t, __wrap_calloc(), __wrap_free(), __wrap_malloc(), __wrap_realloc(), __wrap_strdup(), cbm_mem_profile_alloc(), cbm_mem_profile_alloc_at() (+9 more)

### Community 185 - "Community 185"
Cohesion: 0.23
Nodes (19): slab_page_t, slab_state_t, cbm_aligned_free(), cbm_slab_reclaim(), cbm_slab_reset_thread(), slab_calloc(), slab_free(), slab_grow() (+11 more)

### Community 186 - "Community 186"
Cohesion: 0.12
Nodes (20): yyjson_val, cbm_cli_build_args_json(), cbm_cli_print_tool_help(), cli_closest_prop(), cli_edit_distance(), cli_heap_msgf(), cli_kebab_to_snake(), cli_schema_required_has() (+12 more)

### Community 187 - "Community 187"
Cohesion: 0.22
Nodes (20): bootstrap_config_valid(), bootstrap_deadline_after(), bootstrap_finish_probe(), bootstrap_probe(), bootstrap_probe_is_finishable(), bootstrap_probe_is_waitable(), bootstrap_production_probe(), bootstrap_result_reset() (+12 more)

### Community 188 - "Community 188"
Cohesion: 0.17
Nodes (20): cbm_jsonrpc_request_t, cbm_daemon_frontend_cancellation_matches_request(), frontend_parse_cancellation(), cbm_jsonrpc_request_t, cbm_jsonrpc_parse(), cbm_jsonrpc_request_free(), cbm_mcp_cancel_request_matches(), jsonrpc_parse_array_not_object() (+12 more)

### Community 189 - "Community 189"
Cohesion: 0.30
Nodes (19): CBMLanguage, SUITE, TEST, pipeline_battery(), repro_grammar_functional(), repro_grammar_functional_clojure(), repro_grammar_functional_commonlisp(), repro_grammar_functional_elixir() (+11 more)

### Community 190 - "Community 190"
Cohesion: 0.10
Nodes (20): extract_tsx(), tslsp_jsx_component_resolutions_join_exact_tag_sites(), tslsp_jsx_component_self_closing(), tslsp_jsx_component_with_children(), tslsp_jsx_import_requires_registered_component(), tslsp_jsx_intrinsic_skipped(), tslsp_jsx_local_tag_shadow_blocks_module_component(), tslsp_jsx_nested_component() (+12 more)

### Community 191 - "Community 191"
Cohesion: 0.27
Nodes (19): bootstrap_endpoint_fixture_t, bootstrap_fake_ops_t, cbm_daemon_bootstrap_endpoint_new(), bootstrap_endpoint_fixture_finish(), bootstrap_endpoint_fixture_start(), bootstrap_fake_callbacks(), bootstrap_identity(), cbm_daemon_bootstrap_ops_t (+11 more)

### Community 192 - "Community 192"
Cohesion: 0.15
Nodes (17): fetch_latest_tag(), prefix_icase(), BOOL, DWORD, FILE, PINIT_ONCE, PVOID, wchar_t (+9 more)

### Community 193 - "Community 193"
Cohesion: 0.31
Nodes (18): CBMLanguage, SUITE, TEST, pipeline_battery(), repro_grammar_core(), repro_grammar_core_c(), repro_grammar_core_cpp(), repro_grammar_core_csharp() (+10 more)

### Community 194 - "Community 194"
Cohesion: 0.31
Nodes (18): CBMLanguage, SUITE, TEST, pipeline_battery(), repro_grammar_scripting(), repro_grammar_scripting_dart(), repro_grammar_scripting_groovy(), repro_grammar_scripting_javascript() (+10 more)

### Community 195 - "Community 195"
Cohesion: 0.30
Nodes (18): CBMLanguage, SUITE, TEST, pipeline_battery(), repro_grammar_systems(), repro_grammar_systems_ada(), repro_grammar_systems_cobol(), repro_grammar_systems_crystal() (+10 more)

### Community 196 - "Community 196"
Cohesion: 0.11
Nodes (19): count_resolved(), rustlsp_better_than_treesitter_only(), rustlsp_cov_method_inherent_struct(), rustlsp_cov_method_same_name_different_types(), rustlsp_cov_pat_match_ok_err(), rustlsp_cov_robust_negative_no_cross_type_attribution(), rustlsp_cov_robust_negative_no_phantom_method(), rustlsp_dbg_macro_inner_call() (+11 more)

### Community 197 - "Community 197"
Cohesion: 0.20
Nodes (17): cbm_delta_saved_edge_t, delta_patch_ctx_t, cbm_gbuf_edge_t, cbm_gbuf_node_t, cbm_gbuf_t, cbm_store_t, cbm_delta_free_snapshot(), cbm_delta_patch() (+9 more)

### Community 198 - "Community 198"
Cohesion: 0.25
Nodes (17): cbm_store_generation(), cbm_store_journal_size_limit(), cbm_store_resolve_mmap_size(), SUITE, TEST, clear_mmap_env(), corrupt_page_scan_returns_error_not_truncation(), journal_size_limit_bounds_wal_issue1083() (+9 more)

### Community 199 - "Community 199"
Cohesion: 0.24
Nodes (17): cbm_store_seal_existing_path_for_replace(), cbm_store_seal_for_atomic_publish(), SUITE, TEST, cached_count_queries_release_delete_mode_reader_lock(), cached_node_lookups_release_delete_mode_reader_lock(), checkpoint_does_not_truncate_wal(), dump_install_ignores_stale_wal_sidecar() (+9 more)

### Community 200 - "Community 200"
Cohesion: 0.16
Nodes (13): CBMFileResult, TEST, golden_for(), grammar_code_extracts_defs(), grammar_label_goldens(), label_histogram(), non_module_defs(), CBMFileResult (+5 more)

### Community 201 - "Community 201"
Cohesion: 0.11
Nodes (18): complexity_access_depth_and_params(), complexity_chained_receiver_not_self(), complexity_delegation_receivers_not_recursive_issue876(), complexity_flat_no_loops(), complexity_go_method_receiver_self_recursion(), complexity_guarded_recursion(), complexity_linear_scan_in_loop(), complexity_loop_with_branch() (+10 more)

### Community 202 - "Community 202"
Cohesion: 0.19
Nodes (18): atomic_bool, HANDLE, pid_t, watcher_stop_and_unwatch_cancel_blocked_git_without_backstop(), watcher_test_self_image(), watcher_test_wait_complete(), watcher_test_wait_pid(), watcher_test_wait_process_gone() (+10 more)

### Community 203 - "Community 203"
Cohesion: 0.24
Nodes (16): cbm_yaml_node_t, cbm_yaml_get_str_list(), find_child(), leading_spaces(), navigate(), node_add_child(), node_new(), parse_key_line() (+8 more)

### Community 204 - "Community 204"
Cohesion: 0.21
Nodes (17): cbm_lex(), cbm_lex_free(), lex_single_char(), lex_skip_whitespace_comments(), cypher_lex_ends_keyword(), cypher_lex_full_query(), cypher_lex_in_is_null(), cypher_lex_keywords_case_insensitive() (+9 more)

### Community 205 - "Community 205"
Cohesion: 0.24
Nodes (16): assert_lsp_strategy(), assert_lsp_strategy_files(), assert_no_resolvable_edge(), assert_strategy_absent(), RFile, SUITE, TEST, repro_lsp_ts() (+8 more)

### Community 206 - "Community 206"
Cohesion: 0.27
Nodes (14): main(), SUITE, TEST, cbm_suite_enabled(), repro_runner_filter(), repro_runner_filter_accepts_comma_list(), repro_runner_filter_accepts_space_list(), repro_runner_filter_accepts_suite_substring() (+6 more)

### Community 207 - "Community 207"
Cohesion: 0.20
Nodes (14): BOOL, DWORD, main(), tf_blocking_git_control_handler(), tf_cleanup_cache_sentinel(), tf_invoked_as_blocking_git(), tf_invoked_as_windows_git_module(), tf_maybe_run_blocking_git_probe() (+6 more)

### Community 208 - "Community 208"
Cohesion: 0.29
Nodes (16): CBMFileResult, CBMLanguage, c_clean_file_not_flagged(), c_error_range_points_at_failed_region(), c_ifdef_split_brace_neighbors_still_extracted(), c_ifdef_split_brace_sets_parse_incomplete(), SUITE, TEST (+8 more)

### Community 209 - "Community 209"
Cohesion: 0.39
Nodes (16): kill_pid(), main(), out_text(), _parallel_one_shots(), pid_from(), r"""GREEN guard — daemon stability, parameter surface, and failure modes.…, read_line_with_timeout(), run_cli() (+8 more)

### Community 210 - "Community 210"
Cohesion: 0.23
Nodes (14): FILE, cbm_cli_progress_finish(), cbm_cli_progress_start(), extract_json_field(), extract_kv(), flush_carriage(), on_discover(), on_done() (+6 more)

### Community 211 - "Community 211"
Cohesion: 0.19
Nodes (15): cbm_lex_result_t, cbm_token_type_t, agg_func_name(), heap_strndup(), is_aggregate_tok(), is_string_func_tok(), keyword_lookup(), lex_push() (+7 more)

### Community 212 - "Community 212"
Cohesion: 0.31
Nodes (15): cbm_search_params_t, search_bind_t, search_like_pool_t, like_pool_add(), like_pool_free(), make_like_hint(), search_apply_degree_filter(), search_build_exclude_labels() (+7 more)

### Community 213 - "Community 213"
Cohesion: 0.25
Nodes (14): assets_adopt_bytes(), assets_bytes_verified(), assets_exe_dir(), assets_fill_error(), assets_parse_body(), assets_read_file(), assets_resolve(), assets_stored_copy_path() (+6 more)

### Community 214 - "Community 214"
Cohesion: 0.14
Nodes (15): bootstrap_fake_cohort_acquire(), bootstrap_fake_cohort_release(), bootstrap_fake_handoff(), bootstrap_fake_lock(), bootstrap_fake_probe(), bootstrap_fake_unlock(), cbm_daemon_bootstrap_cohort_t, cbm_daemon_bootstrap_lock_t (+7 more)

### Community 215 - "Community 215"
Cohesion: 0.16
Nodes (15): CBMCall, CBMDefinition, CBMFileResult, count_calls_exact(), decorators_contain(), extract_go_no_filename_in_module_qn(), extract_java_jaxrs_path_composition_issue1005(), extract_java_method_annotations_issue382() (+7 more)

### Community 216 - "Community 216"
Cohesion: 0.20
Nodes (14): cbm_cli_get_version(), cbm_mcp_tool_profile_t, cbm_mcp_initialize_response(), cbm_mcp_initialize_response_for_profile(), cbm_mcp_parse_tool_profile_args(), cbm_mcp_tool_profile_allows_http(), cbm_mcp_tools_list_page(), cbm_mcp_tools_list_range() (+6 more)

### Community 217 - "Community 217"
Cohesion: 0.14
Nodes (14): cbm_language_for_filename(), lang_fn_blade_php_compound_issue258(), lang_fn_cmake(), lang_fn_dockerfile(), lang_fn_gnumakefile(), lang_fn_main_go(), lang_fn_makefile(), lang_fn_makefile_lower() (+6 more)

### Community 218 - "Community 218"
Cohesion: 0.30
Nodes (13): cbm_store_begin_bulk(), cbm_store_drop_indexes(), cbm_store_end_bulk(), bulk_crash_recovery(), bulk_pragma_end_wal_invariant(), bulk_pragma_wal_invariant(), SUITE, TEST (+5 more)

### Community 219 - "Community 219"
Cohesion: 0.19
Nodes (14): cbm_http_server_stop(), cbm_http_server_t, cbm_httpd_activity_t, cbm_httpd_t, th_connect(), th_connect_with_recv_buffer(), th_http_deadline(), th_recv_until_close() (+6 more)

### Community 220 - "Community 220"
Cohesion: 0.31
Nodes (13): assert_calls_callable_sourced(), RFile, SUITE, TEST, repro_invariant_calls(), repro_invariant_calls_c(), repro_invariant_calls_cpp(), repro_invariant_calls_csharp() (+5 more)

### Community 221 - "Community 221"
Cohesion: 0.18
Nodes (14): resp_has_key(), resp_lacks_key(), tool_detect_changes_impact_shape(), tool_detect_changes_since(), tool_sc_compact(), tool_sc_files(), tool_sc_full(), tool_schema_has_edge_types() (+6 more)

### Community 222 - "Community 222"
Cohesion: 0.24
Nodes (12): cbm_githistory_result_t, commit_t, cbm_pipeline_ctx_t, cbm_pipeline_githistory_apply(), cbm_pipeline_pass_githistory(), collect_coupling_cb(), commit_add_file(), commit_free() (+4 more)

### Community 223 - "Community 223"
Cohesion: 0.21
Nodes (12): cbm_agent_cli_exists(), cbm_agent_registry_command_exists(), cbm_find_cli(), find_in_path(), is_executable(), SUITE, TEST, repro221_write_file() (+4 more)

### Community 224 - "Community 224"
Cohesion: 0.29
Nodes (12): SUITE, TEST, lz4(), lz4_bound_positive(), lz4_compression_ratio(), lz4_decompress_wrong_len(), lz4_random_data(), lz4_roundtrip() (+4 more)

### Community 225 - "Community 225"
Cohesion: 0.38
Nodes (12): cbm_expr_t, cbm_expr_type_t, expr_binary(), expr_free(), expr_not(), parse_and_expr(), parse_atom_expr(), parse_depth_enter() (+4 more)

### Community 226 - "Community 226"
Cohesion: 0.24
Nodes (12): cbm_skill_t, cbm_get_skills(), cbm_install_skills(), cli_install_and_uninstall(), cli_install_dry_run(), cli_installed_skill_limits_match_server_contract(), cli_skill_creation(), cli_skill_descriptions_directive() (+4 more)

### Community 227 - "Community 227"
Cohesion: 0.27
Nodes (11): R521File, R521Proj, cbm_store_t, SUITE, TEST, r521_cleanup(), r521_count_routes(), r521_fwd_slashes() (+3 more)

### Community 228 - "Community 228"
Cohesion: 0.18
Nodes (12): bootstrap_cleanup_fail_stop(), bootstrap_production_cohort_acquire(), bootstrap_production_cohort_release(), bootstrap_production_handoff(), bootstrap_production_lock(), bootstrap_production_unlock(), cbm_daemon_bootstrap_cohort_t, cbm_daemon_bootstrap_lock_t (+4 more)

### Community 229 - "Community 229"
Cohesion: 0.17
Nodes (12): csharp_interface(), extract_ts_factory_object_methods_issue341(), go_interface(), has_def_any(), has_def_qn(), java_interface(), nix_attrset_scope_disambiguates_leaf_names(), nix_dotted_attrpath_qualifies_like_nested() (+4 more)

### Community 230 - "Community 230"
Cohesion: 0.25
Nodes (10): CBMLangSpec, CBMLanguage, SUITE, TEST, manifest_match_count(), repro_call_node_manifest(), repro_call_node_manifest_is_unique_and_partitioned(), repro_call_node_manifest_live_membership_matches_expected_primary_boolean() (+2 more)

### Community 231 - "Community 231"
Cohesion: 0.29
Nodes (11): host_http_thread_create_fn, cbm_daemon_host_http_thread_create_failure_lifecycle_for_test(), host_http_thread_schedule_create(), cbm_http_server_cancel_scheduled_run(), cbm_http_server_free(), cbm_http_server_new(), cbm_http_server_schedule_run(), cbm_thread_t (+3 more)

### Community 232 - "Community 232"
Cohesion: 0.25
Nodes (5): mem_override_is_ours(), __wrap__aligned_free(), __wrap_free(), __wrap__msize(), __wrap_realloc()

### Community 233 - "Community 233"
Cohesion: 0.36
Nodes (10): build_parallel_fixture(), RFile, SUITE, TEST, check_sources_exact(), collect_usage_sources_n(), repro_issue787(), repro_issue787_usage_exact_sources() (+2 more)

### Community 234 - "Community 234"
Cohesion: 0.18
Nodes (11): c_imports(), extract_r_box_use_imports_issue218(), go_imports(), has_import(), html_imports_basic(), java_imports(), lua_imports(), ruby_imports() (+3 more)

### Community 235 - "Community 235"
Cohesion: 0.24
Nodes (10): cbm_extract_binary_from_zip(), zip_extract_entry(), zip_read_u16le(), zip_read_u32le(), cli_extract_binary_from_zip(), cli_extract_binary_from_zip_invalid(), cli_extract_binary_from_zip_not_found(), cli_extract_binary_from_zip_path_traversal() (+2 more)

### Community 236 - "Community 236"
Cohesion: 0.31
Nodes (9): posix_directory_owner_trusted(), posix_directory_parent_secure(), posix_directory_transition_secure(), private_directory_tree_open(), diag_posix_file_valid(), cbm_macos_extended_acl_fd_clear(), cbm_macos_extended_acl_fd_is_deny_only(), cbm_macos_extended_acl_fd_is_empty() (+1 more)

### Community 237 - "Community 237"
Cohesion: 0.27
Nodes (9): CBMDefinition, CBMFileResult, CBMLanguage, SUITE, TEST, find_def(), repro_extraction(), repro_issue554_cpp_out_of_line_method_class_qualified() (+1 more)

### Community 238 - "Community 238"
Cohesion: 0.31
Nodes (9): CBMDefinition, CBMFileResult, SUITE, TEST, count_defs_named(), nth_def_named(), repro_issue495(), repro_issue495_cfg_gated_twins_distinct() (+1 more)

### Community 239 - "Community 239"
Cohesion: 0.31
Nodes (9): CBMDefinition, CBMFileResult, SUITE, TEST, find_def_by_name(), repro_new_ts_class_field_arrow(), repro_new_ts_class_field_arrow_call_enclosing_qn(), repro_new_ts_class_field_arrow_method_def_dropped() (+1 more)

### Community 240 - "Community 240"
Cohesion: 0.33
Nodes (9): browse(), free_port(), http_get_json(), list_fixed_drives(), main(), norm(), r"""GREEN regression guard — the UI directory picker enumerates all logical…, Canonical drive key: 'D:\\', 'D:/', 'D:', 'D' -> 'D:'. (+1 more)

### Community 241 - "Community 241"
Cohesion: 0.33
Nodes (8): cbm_rsq_code_t, sig_build_worker(), cbm_rsq_decode(), cbm_rsq_encode(), cbm_rsq_ip(), rsq_fwht(), rsq_init_diag(), rotsq_concurrent_first_encode()

### Community 242 - "Community 242"
Cohesion: 0.33
Nodes (8): cbm_store_t, SUITE, TEST, lsp_resolved_edge_exists(), node_with_qn_suffix(), repro_ts_inherited_method(), repro_ts_inherited_method_call_resolution(), run_ts_inherited_pipeline()

### Community 243 - "Community 243"
Cohesion: 0.33
Nodes (8): SUITE, TEST, zstd(), zstd_bound_positive(), zstd_compress_levels(), zstd_decompress_too_small_output(), zstd_roundtrip(), zstd_roundtrip_large()

### Community 244 - "Community 244"
Cohesion: 0.32
Nodes (8): cbm_cli_checksum_manifest_digest(), cli_checksum_hex_nibble(), cli_checksum_line_digest(), cli_checksum_line_references_archive(), cli_checksum_manifest_path(), cli_checksum_manifest_rejects_invalid_missing_and_conflicting_digest(), cli_checksum_manifest_rejects_oversized_input(), cli_checksum_manifest_requires_exact_filename_and_accepts_star()

### Community 245 - "Community 245"
Cohesion: 0.29
Nodes (8): cbm_extract_binary_from_targz(), gzip_decompress(), is_tar_end_of_archive(), tar_try_extract_binary(), cli_extract_binary_from_targz(), cli_extract_binary_from_targz_invalid_data(), cli_extract_binary_from_targz_not_found(), create_test_targz()

### Community 246 - "Community 246"
Cohesion: 0.25
Nodes (7): cbm_daemon_ipc_connection, cbm_daemon_ipc_endpoint, cbm_daemon_ipc_lifetime_reservation, cbm_daemon_ipc_listener, cbm_daemon_ipc_local_transition, cbm_daemon_ipc_participant_guard, cbm_daemon_ipc_startup_lock

### Community 247 - "Community 247"
Cohesion: 0.39
Nodes (7): SUITE, TEST, cleanup_path_exists(), cleanup_write_sentinel(), repro_harness_cleans_temp_project_after_fixture_write_failure(), repro_harness_cleanup(), repro_harness_cleanup_empty_dbpath_preserves_relative_sidecars()

### Community 248 - "Community 248"
Cohesion: 0.36
Nodes (7): CBMFileResult, SUITE, TEST, count_defs_with_label_local(), count_method_defs_named(), repro_issue333(), repro_issue333_rust_extraction_depth()

### Community 249 - "Community 249"
Cohesion: 0.36
Nodes (7): SUITE, TEST, repro_issue409(), repro_issue409_install_wires_hook_augment_not_blocking_gate(), rp409_mkdirp(), rp409_read_file(), rp409_write_file()

### Community 250 - "Community 250"
Cohesion: 0.36
Nodes (7): cbm_store_t, SUITE, TEST, repro_new_cypher_limit_zero(), repro_new_cypher_limit_zero_returns_no_rows(), repro_new_cypher_limit_zero_with_clause(), setup_limit_store()

### Community 251 - "Community 251"
Cohesion: 0.39
Nodes (6): cbm_store_t, TEST, repro_parallel_edge_determinism(), repro_seq_parallel_equivalence(), rpd_edge_fingerprint(), rpd_index_and_fingerprint()

### Community 252 - "Community 252"
Cohesion: 0.36
Nodes (7): build_fixture(), SUITE, TEST, elapsed_ms(), measure(), py_lsp_scale(), pylsp_scale_linear_growth()

### Community 253 - "Community 253"
Cohesion: 0.43
Nodes (8): CBMFileResult, rustlsp_count_proc_macro_pseudo_calls(), rustlsp_definition_has_decorator(), rustlsp_extra_proc_macro_tokio_main(), rustlsp_extra_proc_macro_tokio_test(), rustlsp_extra_proc_macro_tracing_instrument(), rustlsp_extra_proc_macro_unknown_attr_no_false_edge(), rustlsp_proc_macro_match_requires_exact_attribute_path()

### Community 254 - "Community 254"
Cohesion: 0.38
Nodes (6): build_search_args(), SUITE, TEST, repro_issue581(), repro_issue581_query_rss_stable(), rss_bytes()

### Community 255 - "Community 255"
Cohesion: 0.40
Nodes (5): SUITE, TEST, r520_git(), repro_issue520(), repro_issue520_detect_changes_includes_new_untracked_file()

### Community 257 - "Community 257"
Cohesion: 0.53
Nodes (5): force_kill(), main(), output_text(), r"""GREEN guard — explicit daemon lifecycle (`daemon start|status|stop`).…, run_cli()

### Community 259 - "Community 259"
Cohesion: 0.70
Nodes (4): main(), make_fixture(), rss_kb(), run_series()

### Community 260 - "Community 260"
Cohesion: 0.40
Nodes (5): CBMFileResult, cov_count_strict(), cov_diag_no_resolved_no_calls(), cov_find(), cov_no_crash()

### Community 261 - "Community 261"
Cohesion: 0.40
Nodes (5): CBMFileResult, CBMResolvedCall, find_resolved_with_strategy(), phplsp_regression_prompt_value_not_routed_to_helper(), phplsp_unindexed_receiver_emits_block()

### Community 262 - "Community 262"
Cohesion: 0.60
Nodes (3): fail(), mk_response(), test_vt_gate_zero_tolerance_contract.sh script

### Community 263 - "Community 263"
Cohesion: 0.50
Nodes (4): BOOLEAN, PVOID, ha_deadline_exit_windows(), VOID

### Community 264 - "Community 264"
Cohesion: 0.67
Nodes (4): cbm_daemon_ipc_startup_lock_t, cbm_daemon_runtime_service_start(), runtime_cleanup_fail_stop(), runtime_startup_lock_release_complete()

### Community 265 - "Community 265"
Cohesion: 0.83
Nodes (3): cbm_cypher_max_depth(), cbm_mcp_max_depth(), env_positive_int()

### Community 266 - "Community 266"
Cohesion: 0.50
Nodes (4): cbm_index_worker_result_t, cbm_mcp_supervised_result_disposition_t, cbm_mcp_supervised_result_disposition(), index_supervisor_unsafe_clean_is_never_fallback_or_recovery()

### Community 274 - "Community 274"
Cohesion: 0.67
Nodes (3): main(), make_fixture(), GREEN regression guard — `cli index_repository` honors a non-ASCII repo_path.…

### Community 275 - "Community 275"
Cohesion: 0.67
Nodes (3): main(), r"""GREEN regression guard — the PreToolUse hook augmenter fires on Windows.…, run_cli()

### Community 281 - "Community 281"
Cohesion: 0.67
Nodes (3): yyjson_mut_doc, yyjson_mut_val, test_append_command_hook()

## Knowledge Gaps
- **36 isolated node(s):** `cbm_daemon_ipc_endpoint`, `cbm_daemon_ipc_listener`, `cbm_daemon_ipc_connection`, `cbm_daemon_ipc_startup_lock`, `cbm_daemon_ipc_local_transition` (+31 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **44 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `cbm_store_close()` connect `Cypher query engine` to `MCP command executors`, `Install & agent config upsert`, `MCP JSON-RPC server`, `Community 135`, `Store types & architecture info`, `Graph buffer dump (CBMDump)`, `Daemon runtime IPC frames`, `Hash table & graph buffer utils`, `Daemon update worker`, `Community 151`, `Regression repro tests`, `Community 154`, `Pipeline lifecycle & store`, `Search output & impact analysis`, `Community 169`, `LSP resolution probe tests`, `Community 171`, `Watcher auto-sync`, `Path utils & profiling`, `Node creation probes`, `ADR management & Louvain`, `Community 55`, `Community 58`, `Community 60`, `Community 63`, `Community 64`, `Community 68`, `Community 198`, `Community 199`, `Community 72`, `Community 73`, `Community 202`, `Community 75`, `Community 78`, `Community 81`, `Community 83`, `Community 84`, `Community 86`, `Community 88`, `Community 218`, `Community 93`, `Community 95`, `Community 96`, `Community 98`, `Community 99`, `Community 227`, `Community 101`, `Community 122`, `Community 100`, `Community 102`, `Community 105`, `Community 117`, `Community 250`, `Community 251`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **Why does `cbm_mkdtemp()` connect `Install & agent config upsert` to `Agent registry & profiles`, `Community 134`, `Community 135`, `MCP JSON-RPC server`, `Community 138`, `Store types & architecture info`, `Compile-commands parsing`, `Graph buffer dump (CBMDump)`, `Daemon runtime IPC frames`, `Community 144`, `File discovery & gitignore`, `Daemon update worker`, `Daemon IPC startup lock`, `JSON-like config editor`, `Regression repro tests`, `Community 153`, `Activation transaction (install)`, `Community 151`, `Graph buffer traversal & parallelism`, `Pipeline lifecycle & store`, `Project lock registry`, `Daemon maintenance & version cohort`, `Diagnostics & logging`, `Community 166`, `Community 168`, `LSP resolution probe tests`, `Watcher auto-sync`, `Daemon conflicts & SHA-256`, `Private file locks (Windows)`, `Community 179`, `Node creation probes`, `ADR management & Louvain`, `Community 55`, `Community 58`, `Community 60`, `Community 191`, `Community 63`, `Community 64`, `Community 68`, `Community 72`, `Community 73`, `Community 201`, `Community 75`, `Community 202`, `Community 78`, `Community 83`, `Community 84`, `Community 86`, `Community 88`, `Community 92`, `Community 223`, `Community 95`, `Community 96`, `Community 98`, `Community 227`, `Community 226`, `Community 101`, `Community 100`, `Community 102`, `Community 97`, `Community 105`, `Community 107`, `Community 117`, `Community 118`, `Community 247`, `Community 249`, `Community 122`, `Community 126`, `Community 255`?**
  _High betweenness centrality (0.020) - this node is a cross-community bridge._
- **Why does `cbm_unlink()` connect `Community 117` to `Agent registry & profiles`, `MCP command executors`, `Community 130`, `Install & agent config upsert`, `MCP JSON-RPC server`, `Community 139`, `Daemon runtime IPC frames`, `Daemon application jobs`, `Daemon update worker`, `JSON-like config editor`, `Activation transaction (install)`, `Pipeline lifecycle & store`, `YAML config editor`, `Daemon maintenance & version cohort`, `Diagnostics & logging`, `Watcher auto-sync`, `Daemon conflicts & SHA-256`, `Path utils & profiling`, `Community 56`, `Community 57`, `Community 60`, `Community 192`, `Community 64`, `Community 72`, `Community 201`, `Community 74`, `Community 213`, `Community 101`, `Community 107`, `Community 114`, `Community 244`, `Community 126`?**
  _High betweenness centrality (0.014) - this node is a cross-community bridge._
- **Are the 565 inferred relationships involving `cbm_store_close()` (e.g. with `host_state_free()` and `cbm_gbuf_load_from_db()`) actually correct?**
  _`cbm_store_close()` has 565 INFERRED edges - model-reasoned connections that need verification._
- **Are the 520 inferred relationships involving `cbm_mkdtemp()` (e.g. with `cbm_cmd_install()` and `extract_and_install_binary()`) actually correct?**
  _`cbm_mkdtemp()` has 520 INFERRED edges - model-reasoned connections that need verification._
- **What connects `cbm_daemon_ipc_endpoint`, `cbm_daemon_ipc_listener`, `cbm_daemon_ipc_connection` to the rest of the system?**
  _36 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `C++ Hybrid LSP tests` be split into smaller, more focused modules?**
  _Cohesion score 0.013012642273950945 - nodes in this community are weakly interconnected._