# NS-3 project of integrating blockchain(Tangle) in Internet of Things


In case of any errors:
https://github.com/anyonepaw/BlockchainIoT/tree/master/BlockhainIoT/ns-3.29




//NOTE WHEN WANT PyViz in your program

Then activating the visualizer is a matter of enable the --vis waf option:
./waf configure —disable-werror
./waf --run myprogram --vis
Note: the --vis option only works if the program uses ns3::CommandLine to parse command-line arguments:

main(int argc, char *argv[])
{
   [...]
   CommandLine cmd;
   cmd.Parse (argc, argv);
   [...]
   Simulator::Run ();
 }
