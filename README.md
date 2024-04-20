# vs-code-settings
my vs-code settings


------------------------------------------
{
  "workbench.colorTheme": "Bearded Theme feat. Will",
  "workbench.iconTheme": "eq-material-theme-icons-ocean",
  "editor.fontFamily": "'Fira Code', 'MesloLGS NF'",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "git.autofetch": true,
  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter"
  },
  "[kotlin]": {
    "editor.defaultFormatter": "esafirm.kotlin-formatter"
  },
  "[javascript]": {
    "editor.maxTokenizationLineLength": 2500,
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint",
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    }
  },
  "eslint.alwaysShowStatus": true,
  "task.saveBeforeRun": "always",
  "editor.minimap.enabled": false,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.startupEditor": "none",
  "githubPullRequests.pushBranch": "always",
  "aws.suppressPrompts": {
    "codeWhispererNewWelcomeMessage": true
  },
  "window.zoomLevel": 1,
  "redhat.telemetry.enabled": true,
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "git.confirmSync": false,
  "editor.codeActionsOnSave": {
    "source.organizeImports": "explicit"
  },
  "editor.linkedEditing": true,
  "editor.rulers": [
    {
      "column": 80,
      "color": "#00FF0010"
    },
    {
      "column": 100,
      "color": "#BDB76B15"
    },
    {
      "column": 120,
      "color": "#FA807219"
    }
  ],
  "editor.unicodeHighlight.includeComments": true,
  "emmet.variables": {
    "lang": "en"
  },
  "workbench.colorCustomizations": {
    "[Default Dark Modern]": {
      "tab.activeBorderTop": "#00FF00",
      "tab.unfocusedActiveBorderTop": "#00FF0088",
      "textCodeBlock.background": "#00000055"
    },
    "editor.wordHighlightStrongBorder": "#FF6347",
    "editor.wordHighlightBorder": "#FFD700",
    "editor.selectionHighlightBorder": "#A9A9A9"
  },
  "workbench.editor.revealIfOpen": true,
  "workbench.tree.indent": 20,
  "terminal.integrated.tabs.hideCondition": "never",
  "terminal.integrated.enablePersistentSessions": false,
  "java.configuration.updateBuildConfiguration": "automatic",
  "java.debug.settings.hotCodeReplace": "auto",
  "java.sources.organizeImports.staticStarThreshold": 1,
  "cSpell.diagnosticLevel": "Hint",
  "trailing-spaces.includeEmptyLines": false,
  "java.configuration.runtimes": [
    {
      "name": "JavaSE-1.8",
      "path": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/java/8"
    },
    {
      "name": "JavaSE-11",
      "path": "/home/dikenge/.jdks/semeru-11.0.22"
    },
    {
      "name": "JavaSE-17",
      "path": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/java/17"
    },
    {
      "name": "JavaSE-20",
      "path": "/home/dikenge/.jdks/corretto-20.0.2.1"
    },
    {
      "name": "JavaSE-21",
      "path": "/usr/lib/jvm/jdk-21-oracle-x64",
      "default": true
    }
  ],
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "env": {
        "JAVA_HOME": "/usr/lib/jvm/jdk-21-oracle-x64"
      },
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    },
    "JavaSE-1.8": {
      "overrideName": true,
      "env": {
        "JAVA_HOME": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/java/8"
      },
      "path": "bash",
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    },
    "JavaSE-11": {
      "overrideName": true,
      "env": {
        "JAVA_HOME": "/home/dikenge/.jdks/semeru-11.0.22"
      },
      "path": "bash",
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    },
    "JavaSE-17": {
      "overrideName": true,
      "env": {
        "JAVA_HOME": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/java/17"
      },
      "path": "bash",
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    },
    "JavaSE-20": {
      "overrideName": true,
      "env": {
        "JAVA_HOME": "/home/dikenge/.jdks/corretto-20.0.2.1"
      },
      "path": "bash",
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    },
    "JavaSE-21": {
      "overrideName": true,
      "env": {
        "JAVA_HOME": "/usr/lib/jvm/jdk-21-oracle-x64"
      },
      "path": "bash",
      "args": [
        "--rcfile",
        "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/.bashrc"
      ]
    }
  },
  "terminal.integrated.defaultProfile.linux": "JavaSE-21",
  "maven.terminal.customEnv": [
    {
      "environmentVariable": "JAVA_HOME",
      "value": "/usr/lib/jvm/jdk-21-oracle-x64"
    }
  ],
  "java.import.gradle.java.home": "/usr/lib/jvm/jdk-21-oracle-x64",
  "maven.executable.path": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/maven/latest/bin/mvn",
  "java.import.gradle.home": "/home/dikenge/.config/Code/User/globalStorage/pleiades.java-extension-pack-jdk/gradle/latest",
  "workbench.productIconTheme": "IntelliJ",
  "java.configuration.detectJdksAtStart": false,
  "workbench.sideBar.location": "right",
  "trailing-spaces.backgroundColor": "rgba(255,0,0,0.1)"
}
