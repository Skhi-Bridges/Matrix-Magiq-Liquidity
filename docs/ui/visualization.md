// UI Visualization Component for NRSH and ELXR Telemetry
// Uses React and Recharts for visualization of parachain telemetry data
// For integration with parachain demo
// Copyright © 2025 NRSH/ELXR

import React, { useState, useEffect } from 'react';
import { ApiPromise, WsProvider } from '@polkadot/api';
import { web3FromSource } from '@polkadot/extension-dapp';
import { 
  LineChart, Line, AreaChart, Area, BarChart, Bar, 
  PieChart, Pie, Cell, 
  XAxis, YAxis, CartesianGrid, Tooltip, Legend, 
  ResponsiveContainer, RadialBarChart, RadialBar
} from 'recharts
