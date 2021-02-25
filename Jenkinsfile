
// this will be a major changes
 properties([
  parameters([
    choice(name: 'DraftRelease', choices: ['yes', 'no'], description: 'Releaseing git draft')
  ])
])
node {
    stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}/// d    fbdfggdg
