source "https://rubygems.org"

# Jekyll y sus dependencias
gem "jekyll", "~> 4.3.4"

# Tema Minima
gem "minima", "~> 2.5"

# Plugins de Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Solucionar las advertencias relacionadas con bibliotecas que no estarán en futuras versiones de Ruby
gem "logger"
gem "csv"
gem "ostruct"
gem "base64"

# Solucionar problemas relacionados con sass-embedded
gem "sass-embedded", "~> 1.70.0"

# Windows y JRuby no incluyen archivos de zoneinfo, así que se incluye la gema tzinfo-data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Optimizador de rendimiento para monitorear directorios en Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Fijar la versión de `http_parser.rb` en builds de JRuby ya que las versiones más nuevas no tienen un equivalente en Java.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
