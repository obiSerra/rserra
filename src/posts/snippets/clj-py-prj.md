```
(defproject sitemap-checker "0.1.0-SNAPSHOT"
  :description "FIXME: write description"
  :url "http://example.com/FIXME"
  :license {:name "EPL-2.0 OR GPL-2.0-or-later WITH Classpath-exception-2.0"
            :url "https://www.eclipse.org/legal/epl-2.0/"}
  :dependencies [[org.clojure/clojure "1.10.1"]
                 [clj-python/libpython-clj "1.42"]]
  :main sitemap-checker.main
  :aot [sitemap-checker.main]
  :target-path "target/%s")
