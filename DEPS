vars = {
   "base_url" : "https://github.com/",
   "sdk_url"  : "arunnadesh/repo1.git",
   "ui_url"   : "arunnadesh/repo2.git",

   "project_dir": "projectrepo",
   "ui_revision"    : "v1.0",

   "sdk_dest: "src/libsdk"
   "ui_dest : "src/ui_component"
}


deps = {
  #"src/libsdk": "https://github.com/arunnadesh/repo1.git@master",
  #"src/ui_component": "https://github.com/arunnadesh/repo2.git@v1.0",

  Var("projectrepo") + "/" + Var("sdk_dest"): Var("base_url") + "/" +  Var("sdk_url") + "@" + "master",
  Var("projectrepo") + "/" + Var("ui_dest"): Var("base_url") + "/" +  Var("ui_url") + "@" + Var("ui_revision"),
}

