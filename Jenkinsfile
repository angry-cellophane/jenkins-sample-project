@Library('sample-lib@master123') _

echo 'hello'
println(env['NIO'])
echo "nio id = ${env['NIO']}"

node('master') {
    sh 'echo nio id = $NIO'
    println(env.getEnvironment())
    echo "nio id = ${env['NIO']}"
    sh 'echo nio id = $NIO'
    invalid_command()
    sh 'echo hello'
}
