require 'rake'
require 'panamax_template_validator'

task :default do
  `git remote add source https://github.com/CenturyLinkLabs/panamax-contest-templates.git`
  `git fetch source`

  diff = `git diff --stat=400,380 --diff-filter=ACMRTUXB source/master`
  puts diff
  modified_templates = diff.scan(/[\w-]+.pmx/)

  PanamaxTemplateValidator.validate_file_list(modified_templates)
end
