
require "fileutils"

XCODE_APP_DST = '/Applications/Xcode.app/Contents/PlugIns/IDECodeSnippetLibrary.ideplugin/Contents/Resources/SystemCodeSnippets.codesnippets'
DEV_FOLDER_DST = "/Developer/Library/Xcode/PrivatePlugIns/IDECodeSnippetLibrary.ideplugin/Contents/Resources/SystemCodeSnippets.codesnippets"

# Xcode 4.3 which is stored in an app bundle in /applications
task :app do 
  FileUtils.cp "SystemCodeSnippets.codesnippets", XCODE_APP_DST
end

# Developer folder install of xcode
task :devfolder do
  FileUtils.cp "SystemCodeSnippets.codesnippets", DEV_FOLDER_DST
end
