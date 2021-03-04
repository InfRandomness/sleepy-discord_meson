project('template_sleepy-discord_meson', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3', 'cpp_std=c++14'])

cmake = import('cmake')

sleepy_discord = cmake.subproject('sleepy_discord')
sleepy_discord_lib = sleepy_discord.dependency('sleepy_discord')

executable('template_sleepy-discord_meson',
           'src/main.cpp',
           dependencies: [sleepy_discord_lib],
           install : true)
