source("renv/activate.R")
if (Sys.getenv("CI") != "true") {
  Sys.setenv(http_proxy="http://proxy.gov.si:80")
  Sys.setenv(http_proxy_user="http://proxy.gov.si:80")
  Sys.setenv(https_proxy="http://proxy.gov.si:80")
  Sys.setenv(https_proxy_user="http://proxy.gov.si:80")
  cat("User level rprofile here, how are you doing?\n")
  cat("UMAR proxy is set, hooray!\n")
  options(continue = " ")
  if (interactive()) {
    suppressMessages(require(devtools))
  }
}
