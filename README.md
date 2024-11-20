export function AbstraxionContextProvider({
  children,
  contracts,
  rpcUrl = testnetChainInfo.rpc,
  restUrl = testnetChainInfo.rest,
  stake = false,
  bank,
  callbackUrl,
  treasury,
}: {
  children: ReactNode;
  contracts?: ContractGrantDescription[];
  dashboardUrl?: string;
  rpcUrl?: string;
  restUrl?: string;
  stake?: boolean;
  bank?: SpendLimit[];
  callbackUrl?: string;
  treasury?: string;
}): JSX.Element {
 
}
