<a id="genesis-template-action-hooks"></a>
## Genesis Template Action Hooks

From: [Carrie Dils - Genesis Hook Reference: A Complete List of Hooks & Filters for the Genesis Framework](https://carriedils.com/genesis-hook-reference/)

Hint: To find available action hooks in any theme or plugin, search the codebase for do_action.

<a id="genesiscommentsphp"></a>
### genesis/comments.php

* genesis_before_comments
* genesis_comments
* genesis_after_comments
* genesis_before_pings
* genesis_pings
* genesis_after_pings
* genesis_before_comment_form
* genesis_comment_form
* genesis_after_comment_form

<a id="genesisfooterphp"></a>
### genesis/footer.php

* genesis_before_footer
* genesis_footer
* genesis_after_footer
* genesis_after

<a id="genesisheaderphp"></a>
### genesis/header.php

* genesis_doctype
* genesis_title
* genesis_meta
* genesis_before
* genesis_before_header
* genesis_header
* genesis_after_header

<a id="genesissidebar-altphp"></a>
### genesis/sidebar-alt.php

* genesis_before_sidebar_alt_widget_area
* genesis_sidebar_alt
* genesis_after_sidebar_alt_widget_area

<a id="genesissidebarphp"></a>
### genesis/sidebar.php

* genesis_before_sidebar_widget_area
* genesis_sidebar
* genesis_after_sidebar_widget_area


<a id="genesis-structural-action-hooks"></a>
## Genesis Structural Action Hooks


<a id="genesislibframeworkphp"></a>
### genesis/lib/framework.php

* genesis_before_content_sidebar_wrap
* genesis_before_content
* genesis_before_loop
* genesis_loop
* genesis_after_loop
* genesis_after_content
* genesis_after_content_sidebar_wrap

<a id="genesislibinitphp"></a>
### genesis/lib/init.php

* genesis_pre
* genesis_pre_framework
* genesis_init
* genesis_setup

<a id="genesislibstructurearchivephp"></a>
### genesis/lib/structure/archive.php

* genesis_archive_title_descriptions

<a id="genesislibstructurecommentsphp"></a>
### genesis/lib/structure/comments.php

* genesis_list_comments
* genesis_list_pings
* genesis_before_comment
* genesis_after_comment

<a id="genesislibstructureheaderphp"></a>
### genesis/lib/structure/header.php

* genesis_site_title
* genesis_site_description
* genesis_header_right

<a id="genesislibstructureloopsphp"></a>
### genesis/lib/structure/loops.php


Note that I???m only including HTML5 hooks added in Genesis 2.0+. The old XHTML hooks should be thrown down the garbage disposal.

* genesis_before_while
* genesis_before_entry
* genesis_entry_header
* genesis_before_entry_content
* genesis_entry_content
* genesis_after_entry_content
* genesis_entry_footer
* genesis_after_entry
* genesis_after_endwhile
* genesis_loop_else
* genesis_before_post
* genesis_before_post_title
* genesis_post_title
* genesis_after_post_title
* genesis_before_post_content
* genesis_post_content
* genesis_after_post_content
* genesis_after_post
* genesis_after_endwhile
* genesis_loop_else
* genesis/lib/structure/post.php
* genesis_reset_loops
* genesis/lib/structure/menu.php
* genesis_register_nav_menus
* genesis/lib/admin/menu.php
* genesis_admin_menu
* genesis/lib/classes/admin.php
* genesis_admin_init


<a id="genesis-filter-hooks"></a>
## Genesis Filter Hooks

Hint: To search for what filter hooks are available in any theme or plugin, search the codebase for apply_filters.


<a id="genesis404php"></a>
### /genesis/404.php

* genesis_404_entry_title
* genesis_404_entry_content

<a id="genesislibadmincpt-archive-settingsphp"></a>
### /genesis/lib/admin/cpt-archive-settings.php

* genesis_cpt_archive_settings_page_label
* genesis_cpt_archive_settings_menu_label
* genesis_cpt_archive_settings_capability_ . $this->post_type->name
* genesis_cpt_archive_settings_label

<a id="genesislibadminimport-exportphp"></a>
### /genesis/lib/admin/import-export.php

* genesis_export_options

<a id="genesislibadminterm-metaphp"></a>
### /genesis/lib/admin/term-meta.php

* genesis_term_meta_defaults
* genesis_term_meta
* `genesis_term_meta_{$meta_key*}`

<a id="genesislibadminuser-metaphp"></a>
### /genesis/lib/admin/user-meta.php

* genesis_user_meta_defaults

<a id="genesislibclassesbreadcrumbphp"></a>
### /genesis/lib/classes/breadcrumb.php

* genesis_breadcrumb_args
* genesis_build_crumbs
* genesis_archive_crumb
* genesis_single_crumb
* genesis_home_crumb
* genesis_blog_crumb
* genesis_search_crumb
* genesis_404_crumb
* genesis_page_crumb
* genesis_attachment_crumb
* genesis_post_crumb
* genesis_cpt_crumb
* genesis_category_crumb
* genesis_tag_crumb
* genesis_tax_crumb
* genesis_year_crumb
* genesis_month_crumb
* genesis_day_crumb
* genesis_author_crumb
* genesis_post_type_crumb
* genesis_breadcrumb_link

<a id="genesislibclassesclass-genesis-script-loaderphp"></a>
### /genesis/lib/classes/class-genesis-script-loader.php

* genesis_superfish_args_url
* genesis_toggles

<a id="genesislibclassessanitizationphp"></a>
### /genesis/lib/classes/sanitization.php

* genesis_available_sanitizer_filters

<a id="genesislibfunctionsformattingphp"></a>
### /genesis/lib/functions/formatting.php

* get_the_content_limit_allowedtags
* get_the_content_more_link
* get_the_content_limit
* the_content_limit

<a id="genesislibfunctionsgeneralphp"></a>
### /genesis/lib/functions/general.php

* genesis_sitemap_output
* genesis_canonical_url

<a id="genesislibfunctionsheadphp"></a>
### /genesis/lib/functions/head.php

* genesis_get_seo_meta_description
* genesis_get_seo_meta_keywords
* genesis_get_robots_meta_content
* genesis_pre_load_favicon
* genesis_favicon_url

<a id="genesislibfunctionsimagephp"></a>
### /genesis/lib/functions/image.php

* genesis_get_image_default_args
* genesis_pre_get_image
* genesis_get_image

<a id="genesislibfunctionslayoutphp"></a>
### /genesis/lib/functions/layout.php

* genesis_initial_layouts
* genesis_get_layouts
* genesis_site_layout
* genesis_structural_wrap-{$context}

<a id="genesislibfunctionsmarkupphp"></a>
### /genesis/lib/functions/markup.php

* genesis_markup_{$args[???context???]}
* genesis_markup_{$args[???context???]}_output
* genesis_markup_{$args[???context???]}_open
* genesis_markup_{$args[???context???]}_close
* genesis_markup_open
* genesis_markup_close
* genesis_attr_{$context}
* `genesis_attr_{$context}_output`

<a id="genesislibfunctionsmenuphp"></a>
### /genesis/lib/functions/menu.php

* genesis_superfish_enabled

<a id="genesislibfunctionsoptionsphp"></a>
### /genesis/lib/functions/options.php

* genesis_pre_get_option_{$key}
* genesis_options

<a id="genesislibfunctionswidgetizephp"></a>
### /genesis/lib/functions/widgetize.php

* genesis_register_sidebar_defaults
* genesis_register_widget_area_defaults
* genesis_widget_area_defaults
* genesis_sidebar_title_output

<a id="genesislibinitphp-1"></a>
### /genesis/lib/init.php

* genesis_theme_support_menus
* genesis_theme_support_structural_wraps
* genesis_settings_field
* genesis_seo_settings_field
* genesis_cpt_archive_settings_field_prefix

<a id="genesislibshortcodesfooterphp"></a>
### /genesis/lib/shortcodes/footer.php

* genesis_footer_backtotop_shortcode
* genesis_footer_copyright_shortcode
* genesis_footer_childtheme_link_shortcode
* genesis_footer_genesis_link_shortcode
* genesis_footer_studiopress_link_shortcode
* genesis_footer_wordpress_link_shortcode
* genesis_footer_site_title_shortcode
* genesis_footer_home_link_shortcode
* genesis_footer_loginout_shortcode

<a id="genesislibshortcodespostphp"></a>
### /genesis/lib/shortcodes/post.php

* genesis_post_date_shortcode
* genesis_post_time_shortcode
* genesis_post_modified_date_shortcode
* genesis_post_modified_time_shortcode
* genesis_post_author_shortcode
* genesis_post_author_link_shortcode
* genesis_post_author_posts_link_shortcode
* genesis_post_comments_shortcode
* genesis_post_tags_shortcode
* genesis_post_categories_shortcode
* genesis_post_terms_shortcode
* genesis_edit_post_link
* genesis_post_edit_shortcode

<a id="genesislibstructurearchivephp-1"></a>
### /genesis/lib/structure/archive.php

* genesis_term_intro_text_output
* genesis_author_intro_text_output
* genesis_cpt_archive_intro_text_output

<a id="genesislibstructurecommentsphp-1"></a>
### /genesis/lib/structure/comments.php

* genesis_title_comments
* genesis_prev_comments_link_text
* genesis_next_comments_link_text
* genesis_no_comments_text
* genesis_comments_closed_text
* genesis_title_pings
* genesis_no_pings_text
* genesis_comment_list_args
* genesis_ping_list_args
* comment_author_says_text
* genesis_comment_awaiting_moderation
* genesis_show_comment_date
* genesis_comment_awaiting_moderation
* genesis_comment_form_args

<a id="genesislibstructurefooterphp"></a>
### /genesis/lib/structure/footer.php

* genesis_footer_widget_areas
* genesis_footer_backtotop_text
* genesis_footer_creds_text
* genesis_footer_output
* genesis_footer_scripts

<a id="genesislibstructureheaderphp-1"></a>
### /genesis/lib/structure/header.php

* genesis_viewport_value
* genesis_canonical
* genesis_header_scripts
* genesis_site_title_wrap
* genesis_seo_title
* genesis_site_description_wrap
* genesis_seo_description
* genesis_skip_links_output

<a id="genesislibstructureloopsphp-1"></a>
### /genesis/lib/structure/loops.php

* genesis_custom_loop_args
* genesis_grid_loop_post_class

<a id="genesislibstructurepostphp"></a>
### /genesis/lib/structure/post.php

* genesis_post_title_text
* genesis_link_post_title
* genesis_entry_title_wrap
* genesis_post_title_output
* genesis_post_info
* genesis_edit_post_link
* genesis_post_permalink
* genesis_noposts_text
* genesis_post_meta
* genesis_author_box_gravatar_size
* genesis_author_box_title
* genesis_author_box
* genesis_prev_link_text
* genesis_next_link_text

<a id="genesislibstructuresearchphp"></a>
### /genesis/lib/structure/search.php

* genesis_search_text
* genesis_search_button_text
* genesis_search_form_label
* genesis_search_form

<a id="genesislibwidgetsfeatured-page-widgetphp"></a>
### /genesis/lib/widgets/featured-page-widget.php

* genesis_featured_page_title

<a id="genesislibwidgetsfeatured-post-widgetphp"></a>
### /genesis/lib/widgets/featured-post-widget.php

* genesis_featured_post_title

<a id="genesislibwidgetsuser-profile-widgetphp"></a>
### /genesis/lib/widgets/user-profile-widget.php

* genesis_gravatar_sizes/genesis/search.php
* genesis_search_title_text
* genesis_search_title_output


