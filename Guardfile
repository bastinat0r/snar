# encoding: utf-8
 
require 'guard/guard'
 
module ::Guard
  class Thesis < ::Guard::Guard
    def run_all
    end
 
    def run_on_changes(paths)
      puts "Changes in:\n"
      puts paths
      `rubber --pdf ausarbeitung.tex`
    end
  end
end
 
guard :thesis do
  watch(/^.*\.(tex|bib)$/)
end
