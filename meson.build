project('rlibc', 'rust',
   default_options: [
      'buildtype = minsize',
      'b_lto = true'
   ]
)

rlibc = static_library('rlibc', 'src/rlibc.rs')

rlibc_dep = declare_dependency(link_with: rlibc)
